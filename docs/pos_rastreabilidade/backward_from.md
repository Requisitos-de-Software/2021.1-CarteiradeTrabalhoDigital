# Backward-From

## 1. Introdução

A pós-rastreabilidade Backward-From consiste em descrever as 
ligações existentes entre requisitos e suas fontes

## 2. Metodologia

Para a execução desse método, foi criada uma matriz de rastreabilidade Backward-From contendo os seguintes elementos:

* Requisito: Identificação e descrição do requisito;
* Origem: Documento(s) que serviram de origem para aquele documento;
* Categoria do Meta-Modelo: Categoria do meta-modelo baseada nas categorias de toranzo;
* Tipo do elo: Elo de ligação entre o requisito e suas origens;

### 2.1. Meta-Modelo de Toranzo:

Classifica as informações contidas na matriz em quatro níveis diferentes:

* Ambiental: informações oriundas do contexto no qual a organização
está inserida;
* Organizacional: informações pertencentes à organização (missão,
objetivos e estratégias);
* Gerencial: informações que auxiliam a gerência do projeto, e
* Desenvolvimento: informações associadas aos diversos artefatos
gerados ao longo do processo de desenvolvimento (artefatos de
requisitos, diagramas, códigos, casos de teste e outros).

### 2.2. Tipos de elo:

Os principais elos de rastreabilidade são:

* Satisfação: classe origem tem dependência de satisfação com a classe
destino.
* Recurso: classe origem tem dependência de recurso com a classe
destino.
* Responsabilidade: registra a participação, responsabilidade e ação de
pessoas sobre artefatos.
* Representação: captura a representação ou modelagem dos requisitos
em outras linguagens.
* Alocado: classe origem está relacionada à classe destino, que
representa um subsistema.
* Agregação: indica “composição” de elementos

## 3. Matriz de Rastreabilidade Backward-From

 

| Origem                                               | ID   | Requisito                                                    | Categoria do meta-modelo                                | Tipo do elo                                                  |
| ---------------------------------------------------- | ---- | ------------------------------------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------ |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>;                    | <a href="../../elicitacao/elicitacao/#R01">R01</a>  | O usuário deve ser capaz de se cadastrar no sistema          | Organizacional, <br />Desenvolvimento,<br />Ambiental;  | R01 **representa** Brainstorming, Introspecção. |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>;                    | <a href="../../elicitacao/elicitacao/#R02">R02</a>  | O usuário deve ser capaz de conectar-se a uma conta          | Organizacional, <br />Desenvolvimento;                  | R02 **representa** Brainstorming,  Introspecção.             |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R03">R03</a> | O usuário deve ser capaz de sair de uma conta                | Ambiental,<br />Desenvolvimento;                        | R03 **representa** Brainstorming.                            |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R04">R04</a>  | O usuário deve ser capaz de visualizar seus registros de trabalho | Ambiental, <br />Desenvolvimento;                       | R04 **representa** Brainstorming.                            |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R05">R05</a>  | O usuário deve ser capaz de solicitar ajuda em caso de dúvidas | Organizacional;                                         | R05 **representa** Brainstorming.                            |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>,<br /><a href="../../elicitacao/questionario">Questionário</a>;  | <a href="../../elicitacao/elicitacao/#R06">R06</a> | O usuário deve ser capaz de emitir carteira de trabalho em PDF | Ambiental, <br />Desenvolvimento;                       | R06 **representa** Brainstorming, Introspecção e Questionário. |
| <a href="../../elicitacao/questionario">Questionário</a>;                                        | <a href="../../elicitacao/elicitacao/#R07">R07</a> | O sistema deve ser seguro                                    | Organizacional;                                         | R07 **representa** Questionário.                             |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>,<br /><a href="../../elicitacao/questionario">Questionário</a>; | <a href="../../elicitacao/elicitacao/#R08">R08</a>  | O usuário deve ser capaz de visualizar seus contratos na carteira de trabalho digital | Ambiental,<br /> Organizacional<br /> Desenvolvimento;  | R08 **representa** Brainstorming, Introspecção, Questionário. |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /> <a href="../../elicitacao/introspeccao">Introspecção</a>;                   | <a href="../../elicitacao/elicitacao/#R09">R09</a>  | O usuário deve ser capaz de visualizar suas informações cadastradas no sistema gov.br | Ambiental<br /> Organizacional;                         | R09 **representa** Brainstorming, Introspecção;              |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R10">R10</a>  | O usuário deve conseguir enviar uma foto de identificação própria | Ambiental, <br />Desenvolvimento;                       | R10 **representa** Brainstorming                             |
| <a href="../../elicitacao/questionario">Questionário</a>;                                        | <a href="../../elicitacao/elicitacao/#R11">R11</a>  | O aplicativo deve possuir sistema acessível e simples        | Organizacional;                                         | R11 **representa** Questionário.                             |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>,<br /><a href="../../elicitacao/questionario">Questionário</a>; | <a href="../../elicitacao/elicitacao/#R12">R12</a>  | O usuário deve conseguir reportar divergências de informações em seus contratos | Ambiental, <br />Organizacional,<br /> Desenvolvimento; | R12  **representa** Brainstorming,  Introspecção,  Questionário. |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>,<br /><a href="../../elicitacao/introspeccao">Introspecção</a>;                    | <a href="../../elicitacao/elicitacao/#R13">R13</a>  | O usuário deve ser possível de visualizar anotações em seus contratos | Ambiental, <br />Organizacional,<br /> Desenvolvimento; | R13 **representa** Brainstorming, Introspecção.              |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R14">R14</a>  | O usuário deve conseguir visualizar gráficos de renda dos seus contratos | Ambiental,<br />Organizacional,<br />Desenvolvimento;   | R14 **representa** Brainstorming.                            |
| <a href="../../elicitacao/brainstorming">Brainstorming</a><br /><a href="../../elicitacao/introspeccao">Introspecção</a>,<br /><a href="../../elicitacao/questionario">Questionário</a>;  | <a href="../../elicitacao/elicitacao/#R15">R15</a>  | O usuário deve conseguir solicitar seguro-desemprego pelo aplicativo | Organizacional, <br />Desenvolvimento;                  | R15 **representa** Brainstorming, Introspecção, Questionário. |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R16">R16</a>  | O sistema deve notificar o usuário em caso de qualquer alteração ou anotação no contrato do mesmo | Ambiental;                                              | R16 **representa** Brainstorming.                            |
| <a href="../../elicitacao/brainstorming">Brainstorming</a>;                                       | <a href="../../elicitacao/elicitacao/#R17">R17</a>  | O usuário pode consultar benefícios relacionados ao seu contrato atual | Organizacional,<br />Desenvolvimento;                   | R17 **representa** Brainstorming.                            |
| <a href="../../elicitacao/questionario">Questionário</a>;                                        | <a href="../../elicitacao/elicitacao/#R18">R18</a>  | O usuário deve ter uma melhor experiência de usuário         | Organizacional                                          | R18 **representa** Questionário.                             |

## 4. Referências

* SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 26; Disponível em https://aprender3.unb.br/mod/resource/view.php?id=451521

## 5. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 06/10/2021 | 1.0 | Criação do Documento com a Matriz, Introdução e Metodologia   | Murilo Gomes e Lucas Rodrigues | Giulia Lobo |
| 13/10/2021 | 1.1 | Adição de links para os artefatos | Murilo Gomes | Giulia Lobo|
