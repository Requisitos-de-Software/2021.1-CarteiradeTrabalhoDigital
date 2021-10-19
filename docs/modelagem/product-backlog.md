# Backlog do Produto

## 1. Introdução

Este documento tem como objetivo descrever todas as funcionalidades desejáveis no aplicativo da <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a>, sendo que as funcionalidades devem ser descritas através de épicos e histórias de <a href="../lexicos#usuario">usuários</a>, se encontram os seguintes itens:

* **Tema** em que se encontra o <a href="../lexicos#usuario">usuário</a>;
* **Épicos**: Pode englobar várias histórias de <a href="../lexicos#usuario">usuário</a>;
* **ID**: Identificação da história de <a href="../lexicos#usuario">usuário</a> (US - User Story);
* Descrição das histórias de <a href="../lexicos#usuario">usuários</a> com as seguintes colunas:
    * Eu como...;
    * Desejo...;
    * De modo que...;
* **Critérios de Aceitação** para cada história de <a href="../lexicos#usuario">usuário</a>;
* **Prioridade** de cada história de <a href="../lexicos#usuario">usuário</a> seguindo a técnica de priorização MoSCoW;

## 2. Tema
| ID | DESCRIÇÃO |
|----|-----------|
| TM01 | <a href="../lexicos#usuario">usuário</a> |

## 2. Épicos <span id="Epicos"> </span>
| ID | DESCRIÇÃO | ID RELACIONADO (TEMA) |
|----|-----------|----------------|
| EP01 | Eu como visitante ou <a href="../lexicos#usuario">usuário</a>, desejo administrar uma conta na <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a> | TM01 |
| EP02 | Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#solicitarAjuda">solicitar ajuda</a> pela <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a> caso necessário | TM01 |
| EP03 | Eu como <a href="../lexicos#usuario">usuário</a>, desejo compartilhar minhas informações de <a href="../lexicos#contratos">contratos</a> | TM01 |
| EP04 | Eu como <a href="../lexicos#usuario">usuário</a>, desejo ter informações dos meus <a href="../lexicos#contratos">contratos</a> | TM01 |
| EP05 | Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#solicitarBeneficios">Solicitar benefícios</a> pela <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a> | TM01 |

## 3. Tabela do Backlog

|    ID   |      Tipo     |     Eu como    |      Desejo       | Para que | Critérios de Aceitação | Prioridade | ID RELACIONADO (ÉPICO) |
|-------|-------------|--------------|-----------------|-----------|----------|---------|---------|
|    <a href="#US01">[US01]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | <a href=../casos-de-uso#fazerCadastro>Fazer o cadastro</a> de <a href="../lexicos#usuario">usuário</a> | Eu possa gerenciar a minha carteira de trabalho digital | <a href="#US01">[US01]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US02">[US02]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Fazer o Login de <a href="../lexicos#usuario">usuário</a> | Eu consiga acessar a minha carteira digital | <a href="#US02">[US02]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US03">[US03]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | <a href="../casos-de-uso#fazerLogout">Fazer o logout</a> de <a href="../lexicos#usuario">usuário</a> | Eu consiga fechar minha conta para que somente eu que tenho acesso conseguir acessá-la | <a href="#US03">[US03]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US04">[US04]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Fazer perguntas sobre a <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a> | Eu possa sanar minhas dúvidas sobre a <a href="../lexicos#carteiraDeTrabalhoDigital">Carteira de Trabalho Digital</a> | <a href="#US04">[US04]</a> | Must | <a href="#Epicos">[EP02]</a> |
|    <a href="#US05">[US05]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Fazer perguntas sobre o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a> | eu possa <a href="../casos-de-uso#duvidaSeguro">Eu possa tirar dúvidas sobre como funciona o seguro desempeprego e como solicitá-lo</a> | <a href="#US05">[US05]</a> | Must | <a href="#Epicos">[EP02]</a> |
|    <a href="#US06">[US06]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | <a href="../casos-de-uso#emitir"> Emitir </a> <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho digital</a> em pdf | Eu consiga ter o documento em mãos e sem necessitar de conexão de internet se necessário | <a href="#US06">[US06]</a> | Must | <a href="#Epicos">[EP03]</a> |
|    <a href="#US07">[US07]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Ver os registros de trabalho | Eu possa visualizar registros de trabalho registrados em minha <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho digital</a> | <a href="#US07">[US07]</a> | Must | <a href="#Epicos">[EP04]</a> |
|    <a href="#US08">[US08]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Ver os meus <a href="../lexicos#contratos">contratos</a> | Eu consiga visualizar os meus <a href="../lexicos#contratos">contratos</a> registrados em minha <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho digital</a> | <a href="#US08">[US08]</a> | Must | <a href="#Epicos">[EP04]</a> |
|    <a href="#US09">[US09]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Ver anotações de contrato | eu possa ver as anotações feitas em meus <a href="../lexicos#contratos">contratos</a> na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho digital</a> | <a href="#US09">[US09]</a> | Should | <a href="#Epicos">[EP04]</a> |
|    <a href="#US10">[US10]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Reportar as divergências no contrato | Eu posso reportar e apontar as divergências cadastrais no meu <a href="../lexicos#contratos">contrato</a> na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho digital</a> | <a href="#US10">[US10]</a> | Should | <a href="#Epicos">[EP04]</a> |
|    <a href="#US11">[US11]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Ver <a href="../lexicos#grafico">gráficos</a> dos meus <a href="../lexicos#contratos">contratos</a> | eu possa visualizar em forma de <a href="../lexicos#grafico">gráficos</a> os benefícios e faixa salarial concedida em meus <a href="../lexicos#contratos">contratos</a> | <a href="#US11">[US11]</a> | Could | <a href="#Epicos">[EP04]</a> |
|    <a href="#US12">[US12]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | Solicitar <a href="../lexicos#seguroDesemprego">seguro-desemprego</a> | Eu possa solicitar e acompanhar o meu <a href="../lexicos#seguroDesemprego">seguro-desemprego</a> | <a href="#US12">[US12]</a> | Must | <a href="#Epicos">[EP05]</a> |
|    <a href="#US13">[US13]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | <a href="../casos-de-uso#consultarBeneficio">Consultar Benefício emergencial</a> | eu possa acompanhar a situação da minha solicitação do <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a> | <a href="#US13">[US13]</a> | Must | <a href="#Epicos">[EP05]</a> |
|    <a href="#US14">[US14]</a>    |   Funcional   | <a href="../lexicos#usuario">usuário</a> | <a href="../casos-de-uso#consultarAbono">Consultar Abono Salarial</a> | Eu possa acompanhar a situação e valor do meu <a href="../lexicos#abonoSalarial">Abono Salarial</a> | <a href="#US14">[US14]</a> | Must | <a href="#Epicos">[EP05]</a> |

## 4. Critérios de Aceitação

<span id="US01"> </span>

### <a href="#US01">[US01]</a> Eu, como <a href="../lexicos#usuario">usuário</a>,desejo <a href=../casos-de-uso#fazerCadastro>fazer o cadastro</a> de <a href="../lexicos#usuario">usuário</a>

#### Critérios de aceitação:

- O <a href="../lexicos#usuario">usuário</a> deve ser redirecionado para o sistema de cadastro .gov.br ao entrar no aplicativo sem nenhum cadastro
- Ter uma validação do cpf digitado para cadastro
- Ter uma validação do nome digitado para cadastro
- Ter uma validação do e-mail digitado para cadastro
- Ter uma validação do telefone digitado para cadastro
- Ter uma validação da senha digitada para cadastro
- O <a href="../lexicos#usuario">usuário</a> deve aceitar os termos de uso e políticas de <a href="../lexicos#usuario">usuário</a>
- O <a href="../lexicos#usuario">usuário</a> deve responder perguntas sobre informações contidas no seu cpf para validar sua identidade
- O <a href="../lexicos#usuario">usuário</a> deve ser redirecionado para a página de login e, depois do login, ele é considerado como <a href="../lexicos#usuario">usuário</a>.



<span id="US02"> </span> 

### <a href="#US02">[US02]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo fazer meu login para ter o acesso de <a href="../lexicos#usuario">usuário</a>

#### Critérios de Aceitação:

- Redirecionar o <a href="../lexicos#usuario">usuário</a> para o sistema de login .gov.br

- Ter uma validação para o CPF digitado para login

- Ter uma validação para a senha digitada para login

- Redirecionar o <a href="../lexicos#usuario">usuário</a> para dentro do aplicativo.

  

<span id="US03"> </span>

### <a href="#US03">[US03]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#fazerLogout">fazer o logout</a> de <a href="../lexicos#usuario">usuário</a>

#### Critérios de Aceitação:

- Deve existir uma opção para o <a href="../lexicos#usuario">usuário</a> <a href="../casos-de-uso#fazerLogout">fazer o logout</a> de sua conta
- O <a href="../lexicos#usuario">usuário</a> deve ser redirecionado para a página de login após <a href="../casos-de-uso#fazerLogout">fazer o logout</a>



<span id="US04"></span> 

### <a href="#US04">[US04]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#duvidasCarteira">Tirar dúvidas sobre a carteira de trabalho digital</a>.

#### Critérios de Aceitação:

- Na aba de mais deve existir uma opção que contém respostas para as perguntas mais frequentes feitas sobre a <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a>;
- Também na aba de mais deve existir um canal de conexão com o Ministério do Trabalho e Emprego (MTE) chamado <a href="../lexicos#aloTrabalho">ALÔ TRABALHO</a>; 

<span id="US05"></span>

### <a href="#US05">[US05]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#duvidasCarteira">Tirar dúvidas sobre a carteira de trabalho digital</a>.

#### Critérios de Aceitação:

- Deve existir um local que mostre informações sobre o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>;
- Devem ser disponibilizadas respostas sobre as perguntas mais frequentes sobre o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>;
- Deve ser disponibilizado algum canal de comunicação do <a href="../lexicos#usuario">usuário</a> com o governo para que ele possa tirar alguma dúvida específica sobre o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>;

<span id="US06"></span>

### <a href="#US06">[US06]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo emitir a minha <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>.

#### Critérios de Aceitação:

- Deve existir uma aba chamada <a  href="../lexicos#enviar">enviar</a> que permita o <a href="../lexicos#usuario">usuário</a> <a  href="../lexicos#enviar">enviar</a> as informações na da <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de Trabalho Digital</a> em PDF;
- O <a href="../lexicos#usuario">usuário</a> deve poder escolher quais dados ele quer que sejam mostrados no documento em PDF;





### <a href="#US07">[US07]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo ver os meus registros de trabalho.

#### Critérios de Aceitação:

- Deve existir um local em que o <a href="../lexicos#usuario">usuário</a> possa ver todos os seus registros de trabalho;
- O <a href="../lexicos#usuario">usuário</a> deve ser capaz de ver os detalhes desses registros;



<span id="US08"></span>

### <a href="#US08">[US08]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo ver todos os meus <a href="../lexicos#contratos">contratos</a>.

#### Critérios de Aceitação:

- Deve existir uma aba de <a href="../lexicos#contratos">contratos</a>;
- Nesta aba deve conter informações sobre todos os <a href="../lexicos#contratos">contratos</a> registrados;



<span id="US09"></span>

### <a href="#US09">[US09]</a> - Eu como <a href="../lexicos#usuario">usuário</a>,  desejo ver anotações de contrato.

#### Critérios de Aceitação:

- Deve existir uma tela em que o <a href="../lexicos#usuario">usuário</a> consiga ver os detalhes das três últimas anotações feitas no último contrato vigente, como admissão, demissão, alteração de cargo, período de férias, etc;

<span id="US10"></span>

### <a href="#US10">[US10]</a> - Eu como <a href="../lexicos#usuario">usuário</a>,  desejo reportar <a href="../lexicos#divergenciasContratos">divergências de informações nos contratos</a>.

#### Critérios de Aceitação:

- Ao acessar o contrato, o <a href="../lexicos#usuario">usuário</a> verá se há divergência nas informações dos <a href="../lexicos#contratos">contratos</a>;
- O <a href="../lexicos#usuario">usuário</a> terá um opção para informar para o contratante a divergência do contrato;

<span id="US11"></span>

### <a href="#US11">[US11]</a> - Eu como <a href="../lexicos#usuario">usuário</a>,  desejo ver <a href="../lexicos#grafico">gráficos</a> dos meus <a href="../lexicos#contratos">contratos</a>.

#### Critérios de Aceitação:

- Ao acessar um contrato, o <a href="../lexicos#usuario">usuário</a> deve ter uma opção para visualizar os <a href="../lexicos#grafico">gráficos</a> daquele contrato
- Os <a href="../lexicos#grafico">gráficos</a> devem mostrar informações coerentes com o contrato especificado



<span id="US12"></span>

### <a href="#US12">[US12]</a> - Eu como <a href="../lexicos#usuario">usuário</a>,  desejo solicitar o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>.

#### Critérios de Aceitação:

- Na aba de <a href="../lexicos#beneficios">benefícios</a> deve existir uma opção referente ao <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>
- Deve existir a opção de solicitar o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>



<span id="US13"></span>

### <a href="#US13">[US13]</a> - Eu como <a href="../lexicos#usuario">usuário</a>,  desejo consultar o <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a>

#### Critérios de Aceitação:

- Na aba de <a href="../lexicos#beneficios">benefícios</a> deve existir uma opção referente ao <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a>;
- Deve existir a opção de solicitar o <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a>;
- Deve existir uma opção que mostra as principais informações sobre o <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a>;
- O <a href="../lexicos#usuario">usuário</a> deve obter o feedback da sua solicitação de <a href="../lexicos#beneficioEmergencial">Benefício emergencial</a> quando necessário;



<span id="US14"></span>

### <a href="#US14">[US14]</a> - Eu como <a href="../lexicos#usuario">usuário</a>, desejo <a href="../casos-de-uso#consultarAbono">Consultar Abono Salarial</a>

#### Critérios de Aceitação:

* Na aba de <a href="../lexicos#beneficios">benefícios</a> deve existir uma opção referente ao <a href="../lexicos#abonoSalarial">Abono Salarial</a>
* Deve existir a opção de solicitar o <a href="../lexicos#abonoSalarial">Abono Salarial</a>
* Deve existir uma opção que mostra as principais informações sobre o <a href="../lexicos#abonoSalarial">Abono Salarial</a>
* O <a href="../lexicos#usuario">usuário</a> deve obter o feedback da sua solicitação do <a href="../lexicos#abonoSalarial">Abono Salarial</a>



## 5. Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 15; Disponível em https://aprender3.unb.br/mod/resource/view.php?id=451476

## 6. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 24/08/2021 | 0.1 | Criação do Documento com tema, épico e história de <a href="../lexicos#usuario">usuário</a>. | Liverson Paulo | Denniel William |
| 08/09/2021 | 0.2 | Adição dos critérios de aceitação, introdução ao documento e bibliografia. | Murilo Gomes e Lucas Rodrigues | Denniel William |
| 09/09/2021 | 1.0 | Adição da tabela backlog do produto e remoção da tabela de histórias de <a href="../lexicos#usuario">usuário</a> | Denniel William |  |
| 26/09/2021 | 1.1 | Rastreabilidade do projeto  | Liverson Paulo e Giulia Lobo | Murilo Gomes |
| 19/09/2021 | 1.2 | Reestruturação do "para que" no Product Backlog  | Denniel William | Murilo Gomes  |
