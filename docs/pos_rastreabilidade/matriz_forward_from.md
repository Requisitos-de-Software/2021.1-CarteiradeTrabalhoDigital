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
| <a href="../../elicitacao/elicitacao/#R01">R01</span> | O usuário deve ser capaz de se cadastrar no sistema | <a href="../../modelagem/casos-de-uso/#UC03">UC03</a>, <a href="../../modelagem/product-backlog/#US01">US01</a>, <a href="../../modelagem/cenarios/#C01">C01</a>, <a href="../../modelagem/cenarios/#C02">C02</a> | Funcional | Gerencial, Organizacional | Recurso, Responsabilidade, Representação |
| <a href="../../elicitacao/elicitacao/#R02">R02</span> | O usuário deve ser capaz de se conectar-se a uma conta | <a href="../../modelagem/product-backlog/#US02">US02</a>, <a href="../../modelagem/casos-de-uso/#UC02">UC02</a>, <a href="../../modelagem/cenarios/#C03">C03</a> | Funcional | Gerencial, Organizacional | Satisfação, Recurso e Representação |  
| <a href="../../elicitacao/elicitacao/#R03">R03</span> | O usuário deve ser capaz de sair de uma conta | <a href="../../modelagem/product-backlog/#US03">US03</a>, <a href="../../modelagem/casos-de-uso/#UC03">UC03</a>, <a href="../../modelagem/cenarios/#C04">C04</a> | Funcional | Organizacional | Recurso |
| <a href="../../elicitacao/elicitacao/#R04">R04</span> | O usuário deve ser capaz de visualizar seu registro de trabalho | <a href="../../modelagem/product-backlog/#US07">US07</a>, <a href="../../modelagem/casos-de-uso/#UC12">UC12</a>, <a href="../../modelagem/cenarios/#C05">C05</a>  | Funcional | Organizacional, Ambiental, Gerencial | Representação, Responsabilidade, Alocado e Agregação |
| <a href="../../elicitacao/elicitacao/#R05">R05</span> | O usuário deve ser capaz de solicitar ajuda em caso de dúvidas | <a href="../../modelagem/product-backlog/#US04">US04</a>, <a href="../../modelagem/lexicos/#L02">L02</a>, <a href="../../modelagem/lexicos/#L03">L03</a>, <a href="../../modelagem/casos-de-uso/#UC05">UC05</a>, <a href="../../modelagem/casos-de-uso/#UC06">UC06</a>, <a href="../../modelagem/casos-de-uso/#UC07">UC07</a>  | Funcional | Organizacional | Satisfação, Recurso |
| <a href="../../elicitacao/elicitacao/#R06">R06</span> | O usuário deve ser capaz de emitir carteira de trabalho em pdf | <a href="../../modelagem/product-backlog/#US06">US06</a>, <a href="../../modelagem/casos-de-uso/#UC08">UC08</a>, <a href="../../modelagem/casos-de-uso/#UC09">UC09</a>  | Funcional | Desenvolvimento | Agregação |
| <a href="../../elicitacao/elicitacao/#R07">R07</span> | O sistema deve ser seguro | <a href="../../modelagem/NFR-Framework/#confiabilidade">Diagrama de confiabilidade</a> | Não Funcional | Desenvolvimento | Satisfação, Responsabilidade, Representação, Recurso |
| <a href="../../elicitacao/elicitacao/#R08">R08</span> | O usuário deve ser capaz de visualizar seus contratos de trabalho na carteira digital | <a href="../../modelagem/product-backlog/#US08">US08</a>, <a href="../../modelagem/lexicos/#L09">L09</a>, <a href="../../modelagem/casos-de-uso/#UC10">UC10</a>, <a href="../../modelagem/casos-de-uso/#UC11">UC11</a>, <a href="../../modelagem/cenarios/#C08">C08</a> | Funcional | Ambiental, Gerencial, Organizacional | Responsabilidade, Representação, Agregação, Alocado |
| <a href="../../elicitacao/elicitacao/#R09">R09</span> | O usuário deve visualizar suas informações cadastradas no sistema gov.br | <a href="../../modelagem/casos-de-uso/#UC01">UC01</a>, <a href="../../modelagem/cenarios/#C09">C09</a> | Funcional | Ambiental, Organizacional | Responsabilidade |
| <a href="../../elicitacao/elicitacao/#R10">R10</span> | O usuário deve conseguir mandar uma foto de identificação própria | <a href="../../modelagem/cenarios/#C09">C09</a> | Funcional | Desenvolvimento | Recurso |
| <a href="../../elicitacao/elicitacao/#R11">R11</span> | O aplicativo deve possuir sistema acessível e simples | <a href="../../modelagem/NFR-Framework/#portabilidade">Diagrama de portabilidade</a> | Não Funcional | Desenvolvimento, Gerencial | Representação, Satisfação |
| <a href="../../elicitacao/elicitacao/#R12">R12</span> | O usuário deve conseguir reportar divergências de informações em seus contratos | <a href="../../modelagem/product-backlog/#US10">US10</a>, <a href="../../modelagem/lexicos/#L10">L10</a>, <a href="../../modelagem/cenarios/#C10">C10</a> | Funcional | Ambiental | Representação |
| <a href="../../elicitacao/elicitacao/#R13">R13</span> | O usuário deve ser possível de visualizar anotações em seu contrato | <a href="../../modelagem/product-backlog/#US09">US09</a>, <a href="../../modelagem/cenarios/#C11">C11</a> | Funcional | ---- | Representação |
| <a href="../../elicitacao/elicitacao/#R14">R14</span> | O usuário deve conseguir visualizar gráficos de renda de seus contratos | <a href="../../modelagem/product-backlog/#US11">US11</a>, <a href="../../modelagem/lexicos/#L12">L12</a>, <a href="../../modelagem/cenarios/#C12">C12</a> | Funcional | Ambiental, Organizacional, Gerencial | Agregação, Alocado, Responsabilidade, Recurso |
| <a href="../../elicitacao/elicitacao/#R15">R15</span> | O usuário deve conseguir solicitar seguro-desemprego pelo aplicativo | <a href="../../modelagem/product-backlog/#US12">US12</a>, <a href="../../modelagem/lexicos/#L14">L14</a>, <a href="../../modelagem/casos-de-uso/#UC15">UC15</a>, <a href="../../modelagem/cenarios/#C13">C13</a> | Funcional | Ambiental, Organizacional | Satisfação |
| <a href="../../elicitacao/elicitacao/#R16">R16</span> | O sistema deve notificar o usuário em caso de qualquer alteração ou anotação no contrato do mesmo | <a href="../../modelagem/product-backlog/#US09">US09</a>, <a href="../../modelagem/lexicos/#L13">L13</a>, <a href="../../modelagem/cenarios/#C14">C14</a> | Funcional | Organizacional | Alocado |
| <a href="../../elicitacao/elicitacao/#R17">R17</span> | O usuário pode consultar benefícios relacionados ao seu contrato atual | <a href="../../modelagem/product-backlog/#US13">US13</a>, <a href="../../modelagem/product-backlog/#US14">US14</a>, <a href="../../modelagem/lexicos/#L05">L05</a>, <a href="../../modelagem/lexicos/#L06">L06</a>, <a href="../../modelagem/casos-de-uso/#UC16">UC16</a> | Funcional | Ambiental, Organizacional | Responsabilidade, Representação, Alocado |
| <a href="../../elicitacao/elicitacao/#R18">R18</span> | O usuário deve ter uma melhor experiência de usuário | <a href="../../modelagem/NFR-Framework/#usabilidade">Diagrama de usabilidade</a> | Não Funcional | Gerencial, Desenvolvimento | Representação, Recurso, Alocado |

## 6. Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 06/10/2021 |  1.0   | Criação do documento e finalização do documento | Denniel William | Murilo Gomes |
| 13/10/2021 | 1.1 | Adição de links para os artefatos | Murilo Gomes | |
