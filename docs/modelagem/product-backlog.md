# Backlog do Produto

## 1. Introdução

Este documento tem como objetivo descrever todas as funcionalidades desejáveis no aplicativo da Carteira de Trabalho Digital, sendo que as funcionalidades devem ser descritas através de épicos e histórias de usuários, se encontram os seguintes itens:

* **Tema** em que se encontra o usuário;
* **Épicos**: Pode englobar várias histórias de usuário;
* **ID**: Identificação da história de usuário (US - User Story);
* Descrição das histórias de usuários com as seguintes colunas:
    * Eu como...;
    * Desejo...;
    * De modo que...;
* **Critérios de Aceitação** para cada história de usuário;
* **Prioridade** de cada história de usuário seguindo a técnica de priorização MoSCoW;

## 2. Tema
| ID | DESCRIÇÃO |
|----|-----------|
| TM01 | Usuário |

## 2. Épicos <span id="Epicos"> </span>
| ID | DESCRIÇÃO | ID RELACIONADO (TEMA) |
|----|-----------|----------------|
| EP01 | Eu como visitante ou usuário, desejo administrar uma conta na carteira de trabalho digital | TM01 |
| EP02 | Eu como usuário, desejo solicitar ajuda pela carteira de trabalho digital caso necessário | TM01 |
| EP03 | Eu como usuário, desejo compartilhar minhas informações de contratos | TM01 |
| EP04 | Eu como usuário, desejo ter informações dos meus contratos | TM01 |
| EP05 | Eu como usuário, desejo solicitar benefícios pela carteira de trabalho digital | TM01 |

## 3. Tabela do Backlog

|    ID   |      Tipo     |     Eu como    |      Desejo       | De modo que | Critérios de Aceitação | Prioridade | ID RELACIONADO (ÉPICO) |
|-------|-------------|--------------|-----------------|-----------|----------|---------|---------|
|    <a href="#US01">[US01]</a>    |   Funcional   | Usuário | Fazer o cadastro de usuário | eu consiga me cadastrar | <a href="#US01">[US01]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US02">[US02]</a>    |   Funcional   | Usuário | Fazer o Login de usuário | eu consiga logar na minha conta | <a href="#US02">[US02]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US03">[US03]</a>    |   Funcional   | Usuário | Fazer o Logout de usuário | eu consiga sair | <a href="#US03">[US03]</a> | Must | <a href="#Epicos">[EP01]</a> |
|    <a href="#US04">[US04]</a>    |   Funcional   | Usuário | Fazer perguntas sobre a carteira de trabalho digital | eu possa sanar minhas dúvidas sobre a carteira de trabalho digital | <a href="#US04">[US04]</a> | Must | <a href="#Epicos">[EP02]</a> |
|    <a href="#US05">[US05]</a>    |   Funcional   | Usuário | Fazer perguntas sobre o seguro-desemprego | eu possa sanar minhas dúvidas sobre o seguro-desemprego | <a href="#US05">[US05]</a> | Must | <a href="#Epicos">[EP02]</a> |
|    <a href="#US06">[US06]</a>    |   Funcional   | Usuário | Emitir carteira de trabalho em PDF | eu consiga compartilhar o PDF da carteira de trabalho | <a href="#US06">[US06]</a> | Must | <a href="#Epicos">[EP03]</a> |
|    <a href="#US07">[US07]</a>    |   Funcional   | Usuário | Ver os registros de trabalho | eu consiga ver os meus registros | <a href="#US07">[US07]</a> | Must | <a href="#Epicos">[EP04]</a> |
|    <a href="#US08">[US08]</a>    |   Funcional   | Usuário | Ver os meus contratos | eu possa ver todos os meus contratos | <a href="#US08">[US08]</a> | Must | <a href="#Epicos">[EP04]</a> |
|    <a href="#US09">[US09]</a>    |   Funcional   | Usuário | Ver anotações de contrato | eu possa ver as anotações dos meus contratos | <a href="#US09">[US09]</a> | Should | <a href="#Epicos">[EP04]</a> |
|    <a href="#US10">[US10]</a>    |   Funcional   | Usuário | Reportar as divergências no contrato | eu possa informar quais são as divergencias no contrato | <a href="#US10">[US10]</a> | Should | <a href="#Epicos">[EP04]</a> |
|    <a href="#US11">[US11]</a>    |   Funcional   | Usuário | Ver gráficos dos meus contratos | eu possa ver os gráficos do contrato | <a href="#US11">[US11]</a> | Could | <a href="#Epicos">[EP04]</a> |
|    <a href="#US12">[US12]</a>    |   Funcional   | Usuário | Solicitar seguro-desemprego | eu possa ter o feedback sobre a minha solicitação do seguro-desemprego | <a href="#US12">[US12]</a> | Must | <a href="#Epicos">[EP05]</a> |
|    <a href="#US13">[US13]</a>    |   Funcional   | Usuário | Consultar benefício emergencial | eu possa ter o feedback sobre a minha solicitação do benefício emergencial | <a href="#US13">[US13]</a> | Must | <a href="#Epicos">[EP05]</a> |
|    <a href="#US14">[US14]</a>    |   Funcional   | Usuário | Consultar abono salarial | eu possa ver informações sobre o abono salarial | <a href="#US14">[US14]</a> | Must | <a href="#Epicos">[EP05]</a> |

## 4. Critérios de Aceitação

<span id="US01"> </span>

### <a href="#US01">[US01]</a> Eu, como usuário,desejo fazer o cadastro de usuário

#### Critérios de aceitação:

- O usuário deve ser redirecionado para o sistema de cadastro .gov.br ao entrar no aplicativo sem nenhum cadastro
- Ter uma validação do cpf digitado para cadastro
- Ter uma validação do nome digitado para cadastro
- Ter uma validação do e-mail digitado para cadastro
- Ter uma validação do telefone digitado para cadastro
- Ter uma validação da senha digitada para cadastro
- O usuário deve aceitar os termos de uso e políticas de usuário
- O usuário deve responder perguntas sobre informações contidas no seu cpf para validar sua identidade
- O usuário deve ser redirecionado para a página de login e, depois do login, ele é considerado como usuário.



<span id="US02"> </span> 

### <a href="#US02">[US02]</a> - Eu como usuário, desejo fazer meu login para ter o acesso de usuário

#### Critérios de Aceitação:

- Redirecionar o usuário para o sistema de login .gov.br

- Ter uma validação para o CPF digitado para login

- Ter uma validação para a senha digitada para login

- Redirecionar o usuário para dentro do aplicativo.

  

<span id="US03"> </span>

### <a href="#US03">[US03]</a> - Eu como usuário, desejo fazer o logout de usuário

#### Critérios de Aceitação:

- Deve existir uma opção para o usuário fazer o logout de sua conta
- O usuário deve ser redirecionado para a página de login após fazer o logout



<span id="US04"></span> 

### <a href="#US04">[US04]</a> - Eu como usuário, desejo tirar dúvidas sobre a Carteira de Trabalho Digital.

#### Critérios de Aceitação:

- Na aba de mais deve existir uma opção que contém respostas para as perguntas mais frequentes feitas sobre a carteira de trabalho digital;
- Também na aba de mais deve existir um canal de conexão com o Ministério do Trabalho e Emprego (MTE) chamado ALÔ TRABALHO; 

<span id="US05"></span>

### <a href="#US05">[US05]</a> - Eu como usuário, desejo tirar dúvidas sobre a Carteira de Trabalho Digital.

#### Critérios de Aceitação:

- Deve existir um local que mostre informações sobre o seguro-desemprego;
- Devem ser disponibilizadas respostas sobre as perguntas mais frequentes sobre o seguro-desemprego;
- Deve ser disponibilizado algum canal de comunicação do usuário com o governo para que ele possa tirar alguma dúvida específica sobre o seguro-desemprego;

<span id="US06"></span>

### <a href="#US06">[US06]</a> - Eu como usuário, desejo emitir a minha carteira de trabalho.

#### Critérios de Aceitação:

- Deve existir uma aba chamada enviar que permita o usuário enviar as informações na da Carteira de Trabalho Digital em PDF;
- O usuário deve poder escolher quais dados ele quer que sejam mostrados no documento em PDF;





### <a href="#US07">[US07]</a> - Eu como usuário, desejo ver os meus registros de trabalho.

#### Critérios de Aceitação:

- Deve existir um local em que o usuário possa ver todos os seus registros de trabalho;
- O usuário deve ser capaz de ver os detalhes desses registros;



<span id="US08"></span>

### <a href="#US08">[US08]</a> - Eu como usuário, desejo ver todos os meus contratos.

#### Critérios de Aceitação:

- Deve existir uma aba de contratos;
- Nesta aba deve conter informações sobre todos os contratos registrados;



<span id="US09"></span>

### <a href="#US09">[US09]</a> - Eu como usuário,  desejo ver anotações de contrato.

#### Critérios de Aceitação:

- Deve existir uma tela em que o usuário consiga ver os detalhes das três últimas anotações feitas no último contrato vigente, como admissão, demissão, alteração de cargo, período de férias, etc;

<span id="US10"></span>

### <a href="#US10">[US10]</a> - Eu como usuário,  desejo reportar divergências de informações nos contratos.

#### Critérios de Aceitação:

- Ao acessar o contrato, o usuário verá se há divergência nas informações dos contratos;
- O usuário terá um opção para informar para o contratante a divergência do contrato;

<span id="US11"></span>

### <a href="#US11">[US11]</a> - Eu como usuário,  desejo ver gráficos dos meus contratos.

#### Critérios de Aceitação:

- Ao acessar um contrato, o usuário deve ter uma opção para visualizar os gráficos daquele contrato
- Os gráficos devem mostrar informações coerentes com o contrato especificado



<span id="US12"></span>

### <a href="#US12">[US12]</a> - Eu como usuário,  desejo solicitar o seguro-desemprego.

#### Critérios de Aceitação:

- Na aba de benefícios deve existir uma opção referente ao seguro-desemprego
- Deve existir a opção de solicitar o seguro-desemprego



<span id="US13"></span>

### <a href="#US13">[US13]</a> - Eu como usuário,  desejo consultar o benefício emergencial

#### Critérios de Aceitação:

- Na aba de benefícios deve existir uma opção referente ao benefício emergencial;
- Deve existir a opção de solicitar o benefício emergencial;
- Deve existir uma opção que mostra as principais informações sobre o benefício emergencial;
- O usuário deve obter o feedback da sua solicitação de benefício emergencial quando necessário;



<span id="US14"></span>

### <a href="#US14">[US14]</a> - Eu como usuário, desejo consultar abono salarial

#### Critérios de Aceitação:

* Na aba de benefícios deve existir uma opção referente ao abono salarial
* Deve existir a opção de solicitar o abono salarial
* Deve existir uma opção que mostra as principais informações sobre o abono salarial
* O usuário deve obter o feedback da sua solicitação do abono salarial



## 5. Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 15; Disponível em https://aprender3.unb.br/mod/resource/view.php?id=451476

## 6. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 24/08/2021 | 0.1 | Criação do Documento com tema, épico e história de usuário. | Liverson Paulo | Denniel William |
| 08/09/2021 | 0.2 | Adição dos critérios de aceitação, introdução ao documento e bibliografia. | Murilo Gomes e Lucas Rodrigues | Denniel William |
| 09/09/2021 | 1.0 | Adição da tabela backlog do produto e remoção da tabela de histórias de usuário | Denniel William |  |