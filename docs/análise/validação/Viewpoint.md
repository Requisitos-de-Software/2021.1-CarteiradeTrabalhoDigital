# ViewPoint

## 1. Introdução

A análise e comparação utilizando a técnica de viewpoint é um processo informal proposto por Ross 'SADT e Mullery's CORE, eles são semelhantes ao que chamamos de "uso de verificação informal" e dependem fortemente de serem realizados por um bom analista de sistemas. Em suma, a técnica de ponto de vista é um processo que identifica discrepâncias entre duas diferentes visões, classifica e avalia essas discrepâncias e integra as soluções alternativas em uma única representação.

As discrepâncias são classificadas de três maneiras:

* Informação Errada
    * Contradição entre os dois pontos de vista

* Informação Faltante
    * Hierarquias incompletas de acordo com os fatos das regras
    * Regras faltantes
    * Fatos faltantes

* Inconsistências
    * Contradição entre um fato e uma hierarquia
    * Redundância em um mesmo ponto de vista

## 2. Domínio

O domínio utilizado para os dois pontos de vista é o próprio domínio geral da aplicação, tendo como base todos os artefatos gerados.


## 3. Perspectivas
	
Dentro do contexto de uma view existem três perspectivas possíveis: Universo de discurso, perspectiva
de processo (ou regras) e hierarquia. Neste documento só irão ser utilizadas perspectiva de processo e hierarquia

## 4. ViewPoints

### ViewPoint A

```
Perspectiva de Processo:
    ((usuario =id-usuario =cpf =data-nascimento =sexo =nacionalidade =nome-civil)
    (contrato =id-contrato =contratado =cnpj-empresa =nome-empresa =salario =cargo =data-admissao =data-demissao)
    (anotacao =id-anotacao =descricao =data)
    (carteira-de-trabalho =id-carteira =numero =serie =data-emissao)
    (grafico =id-grafico)
    (beneficio =id-beneficio =nome =descricao))

Hierarquia:
(é-um
    (agente (usuario))
    (objeto (contrato anotacao carteira-de-trabalho grafico beneficio)))

(parte-de
	(objeto (usuario id-usuario cpf data-nascimento sexo nacionalidade nome-civil)
		(carteira-de-trabalho id-carteira numero serie data-emissao))
	(objeto (carteira-de-trabalho id-carteira numero serie data-emissao)
		(contrato id-contrato contratado cnpj-empresa nome-empresa salario cargo data-admissao data-demissao))
	(objeto (contrato id-contrato contratado cnpj-empresa nome-empresa salario cargo data-admissao data-demissao)
		(anotacao id-anotacao descricao data))
	(objeto (contrato id-contrato contratado cnpj-empresa nome-empresa salario cargo data-admissao data-demissao)
		(grafico id-grafico))

```	

### ViewPoint B

```
Perspectiva de Processo:
    ((usuario =id-usuario =cpf =data-nascimento =sexo =nacionalidade =nome-civil)
    (contrato =id-contrato =contratado =empresa =salario =cargo =data-admissao =data-demissao)
    (empresa =id-empresa =nome =cnpj)
    (anotacao =id-anotacao =descricao =data)
    (carteira-de-trabalho =id-carteira =numero =serie =data-emissao)
    (grafico =id-grafico)
    (beneficio =id-beneficio =nome =descricao)
    (foto =url))

Hierarquia:
(é-um
    (agente (usuario))
    (objeto (contrato foto empresa anotacao carteira-de-trabalho grafico beneficio))

(parte-de
	(objeto (usuario id-usuario cpf data-nascimento sexo nacionalidade nome-civil)
		    (carteira-de-trabalho id-carteira numero serie data-emissao))
    (objeto (usuario id-usuario cpf data-nascimento sexo nacionalidade nome-civil)
		    (foto url))
	(objeto (usuario id-usuario cpf data-nascimento sexo nacionalidade nome-civil)
	    	(contrato id-contrato contratado empresa salario cargo data-admissao data-demissao))
	(objeto (empresa id-empresa nome cnpj)
		    (contrato id-contrato contratado empresa salario cargo data-admissao data-demissao))
	(objeto (contrato id-contrato contratado cnpj-empresa nome-empresa salario cargo data-admissao data-demissao)
		    (anotacao id-anotacao descricao data))
	(objeto (contrato id-contrato contratado cnpj-empresa nome-empresa salario cargo data-admissao data-demissao)
		    (grafico id-grafico))

```

## 5. Discrepâncias

* Informação Errada
    * No ViewPoint B o contrato faz parte de usuário, sendo que, um contrato trabalhista é sempre associado com a carteira de trabalho;
    * No ViewPoint A as informações da empresa fazem parte diretamente do contrato, sendo que empresa poderia ser um objeto e o contrato fazer parte da empresa.

* Informação Faltante
    * Objeto - foto (A)
    * Objeto - empresa (A)
    * Ação - solicitar benefício (A e B)
    * Ação - emitir carteira em PDF (A e B)
    * Objeto - notificações (A e B)

* Inconsistências
    * Não foi encontrada nenhuma inconsistência em nenhum dos ViewPoints.

## 6. Avaliação

Esta fase consiste em propor uma solução que integra as partes certas dos dois ViewPoints e que corrija os erros encontrados nas mesmas.

A solução B contém menos discrepâncias, por isso ela pode ser utilizada como base, para obter a melhor solução, basta adicionar as informações faltantes em B (solicitar benefício, emitir carteira e notificações) e fazer com que um contrato faça parte da carteira de trabalho e não diretamente do usuário.

## 7. Referências

* do Prado Leite, Julio Cesar Sampaio, and Peter Freeman. "Requirements validation through viewpoint resolution." IEEE Trans. Software Eng. 17.12 (1991): 1253-1269.

* Messaoudi, Mohammed. "Requirements Engineering Through Viewpoints." International Journal of Computing 2.2 (2013): 49-59.

## 8. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 16/09/2021 | 1.0 | Criação do Documento com os Viewpoints e suas devidas explicações e conclusões  | Murilo Gomes | Giulia Lobo |

