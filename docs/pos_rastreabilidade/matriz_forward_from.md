# Matriz Forward From

## 1. Objetivo

Esse documento tem como objetivo definir a rastreabilidade dos requisitos demonstrando através de uma "Matriz forward from".

## 2. Metodologia

A metodologia utilizada para o desenvolvimento desse documento foi baseado no **Meta-Modelo de Toranzo** elaborado em conjunto com o conceito de uma **rastreabilidade forward-from**.

O meta-modelo de Toranzo define que as informações podem ser classificadas em quatro níveis:

  * **Ambiental**: Informações oriundas do contexto no qual a organização está inserida;
  * **Organizacional**: Informações pertencentes à organização (missão, objetivos e estratégias);
  * **Gerencial**: Informações que auxiliam a gerência do projeto; 
  * **Desenvolvimento**: Informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros);

Os principais elos de rastreabilidade são: 

* **Satisfação**: Classe origem tem dependência de satisfação com a classe destino.
* **Recurso**: Classe origem tem dependência de recurso com a classe destino.
* **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
* **Representação**: Captura a representação ou modelagem de requisitos em outras linguagens.
* **Alocado**: Classe origem está relacionada à classe destino, que representa um subsistema.
* **Agregação**: Indica "composição" de elementos.

Já a rastreabilidade forward-from se trata da orientação quanto a ligação dos documentos de requisitos a artefatos de desenho e implementação, ou seja, essa orientação é feita de forma "*forward-from*" que pode ser traduzido como "a partir de", ou "para frente".

Sendo assim, para demonstração, será montada uma matriz com cada requisito tendo seu artefato, categoria meta-modelo e seu elo demonstrado abaixo.

## 3. Matriz Forward From

| ID | Requisito | Artefato | Tipo | Categoria meta-modelo | Elo de rastreabilidade |
|----|-----------|----------|------|-----------------------|-----|
| <a href="../../elicitacao/elicitacao/#R01">R01</span> | O usuário deve ser capaz de se cadastrar no sistema | UC03, US01, C01, C02 | Funcional | Gerencial, Organizacional | Recurso, Responsabilidade, Representação |
| <a href="../../elicitacao/elicitacao/#R02">R02</span> | O usuário deve ser capaz de se conectar-se a uma conta | US02, UC02, C03 | Funcional | Gerencial, Organizacional | Satisfação, Recurso e Representação |  
| <a href="../../elicitacao/elicitacao/#R03">R03</span> | O usuário deve ser capaz de sair de uma conta | US03, UC03, C04 | Funcional | Organizacional | Recurso |
| <a href="../../elicitacao/elicitacao/#R04">R04</span> | O usuário deve ser capaz de visualizar seu registro de trabalho | US07, UC12, C05  | Funcional | Organizacional, Ambiental, Gerencial | Representação, Responsabilidade, Alocado e Agregação |
| <a href="../../elicitacao/elicitacao/#R05">R05</span> | O usuário deve ser capaz de solicitar ajuda em caso de dúvidas | US04, L02, L03, UC05, UC06, UC07  | Funcional | Organizacional | Satisfação, Recurso |
| <a href="../../elicitacao/elicitacao/#R06">R06</span> | O usuário deve ser capaz de emitir carteira de trabalho em pdf | US06, UC08, UC09  | Funcional | Desenvolvimento | Agregação |
| <a href="../../elicitacao/elicitacao/#R07">R07</span> | O sistema deve ser seguro | Diagrama de confiabilidade | Não Funcional | Desenvolvimento | Satisfação, Responsabilidade, Representação, Recurso |
| <a href="../../elicitacao/elicitacao/#R08">R08</span> | O usuário deve ser capaz de visualizar seus contratos de trabalho na carteira digital | US08, L09, UC10, UC11, C08 | Funcional | Ambiental, Gerencial, Organizacional | Responsabilidade, Representação, Agregação, Alocado |
| <a href="../../elicitacao/elicitacao/#R09">R09</span> | O usuário deve visualizar suas informações cadastradas no sistema gov.br | UC01, C09 | Funcional | Ambiental, Organizacional | Responsabilidade |
| <a href="../../elicitacao/elicitacao/#R10">R10</span> | O usuário deve conseguir mandar uma foto de identificação própria | C09 | Funcional | Desenvolvimento | Recurso |
| <a href="../../elicitacao/elicitacao/#R11">R11</span> | O aplicativo deve possuir sistema acessível e simples | Diagrama de portabilidade | Não Funcional | Desenvolvimento, Gerencial | Representação, Satisfação |
| <a href="../../elicitacao/elicitacao/#R12">R12</span> | O usuário deve conseguir reportar divergências de informações em seus contratos | US10, L10, C10 | Funcional | Ambiental | Representação |
| <a href="../../elicitacao/elicitacao/#R13">R13</span> | O usuário deve ser possível de visualizar anotações em seu contrato | US09, C11 | Funcional | ---- | Representação |
| <a href="../../elicitacao/elicitacao/#R14">R14</span> | O usuário deve conseguir visualizar gráficos de renda de seus contratos | US11, L12, C12 | Funcional | Ambiental, Organizacional, Gerencial | Agregação, Alocado, Responsabilidade, Recurso |
| <a href="../../elicitacao/elicitacao/#R15">R15</span> | O usuário deve conseguir solicitar seguro-desemprego pelo aplicativo | US12, L14, UC15, C13 | Funcional | Ambiental, Organizacional | Satisfação |
| <a href="../../elicitacao/elicitacao/#R16">R16</span> | O sistema deve notificar o usuário em caso de qualquer alteração ou anotação no contrato do mesmo | US09, L13, C14 | Funcional | Organizacional | Alocado |
| <a href="../../elicitacao/elicitacao/#R17">R17</span> | O usuário pode consultar benefícios relacionados ao seu contrato atual | US13, US14, L05, L06, UC16, UC16 | Funcional | Ambiental, Organizacional | Responsabilidade, Representação, Alocado |
| <a href="../../elicitacao/elicitacao/#R18">R18</span> | O usuário deve ter uma melhor experiência de usuário | Diagrama de usabilidade | Não Funcional | Gerencial, Desenvolvimento | Representação, Recurso, Alocado |

## 6. Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 06/10/2021 |  1.0   | Criação do documento e finalização do documento | Denniel William | |
