# Casos de uso

## 1. Introdução

<p>Esse artefato é uma técnica que descreve como o usuário realizará as tarefas, dependendo do contexto do software. Descrevendo o ponto do usuário e como o sistema responde as ações, os casos de uso são sequências de passos que são descritos a partir do fluxo.</p>

<p>Os casos de uso integram os requisitos em um pacote abrangente que descreve a interação do usuário com o sistema. Eles começam onde o processo de coleta de requisitos termina. Os requisitos determinam quais Casos de Uso o sistema terá, e muitos dos requisitos se tornarão sua lógica de negócios.</p>

## 2. Metodologia

<p>Para construir o nosso diagrama de casos de uso, primeiramente pegamos de base os requisitos que foram levantados na fase de elicitação.</p>
<p>A partir desses requisitos, foi contruído um product backlog com todos os épicos e as histórias com as quais o grupo irá trabalhar.</p>
<p>E, por último, foram pensadas as relações existentes entre as hgistórias criadas e desenhado o respectivo diagrama.</p>

## 3. Diagrama de casos de uso

### 3.1 Versão 1.0

<img src="../assets/caso_de_uso.jpg"/>
<br/>

**Figura 1:** Diagrama de casos de uso. 
**Autor(es)**: Grupo.

### 3.2 Versão 2.0

<img src="../assets/caso_de_uso_v2.jpg"/>
<br/>

**Figura 1:** Diagrama de casos de uso v2. 
**Autor(es)**: Denniel William e Giulia Lobo.



## 4. Especificação dos casos de uso

### UC01 - Administrar conta

|   UC01   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet |
| **Pós-condições** | Usuário estará logado no sistema <br/> Usuário terá carteira de trabalho digital |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário inicia o aplicativo:** <br/> 1. Usuário inicia o aplicativo <br/> 2. Usuário clica em entrar |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet** | 

### UC02 - Fazer login

|   UC02   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve ter uma conta registrada com CPF próprio <br/> |
| **Pós-condições** | Usuário estará logado no sistema. <br/> Usuário conseguirá acessar funcionalidades do sistema. |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário inicia o aplicativo:** <br/> 1. Usuário inicia o aplicativo; <br/> 2. Usuário clica em entrar; <br/> 3. Inserir CPF; <br/> 4. Clicar em Avançar; <br/> 5. Digitar senha; <br/> 6. Clicar em Entrar; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet** <br/> **[FE02] CPF inválido:** <br/> No passo 3 do [FP01] foi inserido um CPF inválido ou não cadastrado <br/> **[FE03] Senha incorreta:** <br/> No passo 5 do [FP01] foi inserido uma senha não correspondente a conta cadastrada | 

### UC03 - Fazer cadastro

|   UC03   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve ter CPF próprio <br/> |
| **Pós-condições** | Usuário estará logado no sistema. <br/> Usuário terá conta cadastrada na carteira de trabalho digital |
| **Fluxo principal** | **[FP01] Fluxo iniciado ao clicar em Crie sua conta na página de login:** <br/> 1. Usuário seleciona a opção de cadastro; <br/> 2. Usuário confirma suas informações entre as informações visualizadas; <br/> 3. Usuário digita e confirma senha <br/> 4. Usuário valida se não é um robô; <br/> 5. Usuário confirma cadastro; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet** <br/> **[FE02] Informação inválida:** <br/> No passo 2 do [FP01] o usuário escolhe uma ou mais informações erradas sobre seu registro governamental <br/> **[FE03] Senhas incompatíveis:** <br/> No passo 3 do [FP01] usuário digita senha diferentes no campo de digitar e confirmar senha <br/> **[FE04] Senhas inválida:** <br/> No passo 3 do [FP01] usuário digita que não esteja de acordo ao explicitado nas regras do cadastro | 

### UC04 - Fazer logout

|   UC04   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve ter uma conta registrada com CPF próprio <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário será desconectado do sistema.|
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em "Mais" nas opções do aplicativo; <br/> 2. Usuário clica em Sair; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** | 

### UC05 - Solicitar ajuda

|   UC05   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário visualizou as opções de perguntas do aplicativo |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em "Mais" nas opções do aplicativo; <br/> 2. Usuário visualiza as opções de perguntas; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** | 

### UC06 - Tirar dúvidas sobre a carteira de trabalho digital

|   UC06   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário presente na página de perguntas frequentes da carteira de trabalho digital |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário clica em mais opções no aplicativo:** <br/> 1. Usuário clica em perguntas frequentes carteira de trabalho digital; <br/> 2. Usuário percorre a página a procura de perguntas para sanar sua dúvida; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Página gov.br com serviço indisponível** | 

### UC07 - Tirar dúvidas sobre o seguro desemprego

|   UC07   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário presente na página de perguntas frequentes seguro desemprego |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário clica em mais opções no aplicativo:** <br/> 1. Usuário clica em perguntas frequentes seguro desemprego; <br/> 2. Usuário percorre a página a procura de perguntas para sanar sua dúvida; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Página gov.br com serviço indisponível** | 

### UC08 - Compartilhar informações de trabalho

|   UC08   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário é capaz de visualizar as informações cadastradas por ele |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está cadastrado no aplicativo** <br/> 1. Usuário clica no ícone do usuário nas opções do aplicativo; <br/> 2. Usuário visualiza as informações cadastradas; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>**| 

### UC09 - Emitir carteira de trabalho em PDF

|   UC09   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo |
| **Pós-condições** | Usuário é capaz de visualizar as informações cadastradas por ele |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está cadastrado no aplicativo** <br/> 1. Usuário clica em enviar na barra inferior do aplicativo; <br/> 2. Usuário seleciona as informações que deseja gerar no pdf; <br/> 3. Usuário clica no ícone do PDF; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Falha ao visualizar PDF <br/>** | 

### UC10 - Visualizar informações contratuais

|   UC10   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em contratos na barra inferior do aplicativo; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não possui contratos <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**| 

### UC11 - Mostrar contratos

|   UC11   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em contratos na barra inferior do aplicativo; <br/> 2. Usuário visualiza contratos registrados na carteira de trabalho |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não possui contratos <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|

### UC12 - Mostrar registros de trabalho

|   UC12   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os registros de trabalho dos contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em contratos na barra inferior do aplicativo; <br/>  2. Usuário seleciona um contrato; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não possui contratos <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|

### UC13 - Solicitar benefícios

|   UC13   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em Benefícios na barra inferior do aplicativo; <br/> 2. Usuário visualiza benefícios da carteira de trabalho |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não tem permissão para solicitar qualquer benefício <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|

### UC14 - Solicitar outros benefícios

|   UC14   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em Benefícios na barra inferior do aplicativo; <br/> 2. Usuário visualiza benefícios da carteira de trabalho |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não tem permissão para solicitar qualquer benefício <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|

### UC15 - Consultar benefício emergencial

|   UC15   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em Benefícios na barra inferior do aplicativo; <br/> 2. Usuário clica em consultar benefício emergencial; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não tem permissão para solicitar benefício <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|

### UC16 - Consultar abono salarial

|   UC16   | Descrição |
| -------- | --------- |
| **Ator** | Usuário |
| **Pré-condições** | Usuário deve ter conexão a internet <br/> Usuário deve estar logado no aplicativo <br/> Usuário deve ter contratos registrado na conta |
| **Pós-condições** | Usuário é capaz de visualizar os contratos registrados em sua carteira de trabalho |
| **Fluxo principal** | **[FP01] Fluxo iniciado quando um usuário está logado no aplicativo** <br/> 1. Usuário clica em Benefícios na barra inferior do aplicativo; <br/> 2. Usuário clica em consultar abono salarial; |
| **Fluxo(s) alternativo(s)** | - |
| **Fluxo(s) de exceção** | **[FE01] Falha de conexão com a internet <br/>** **[FE02] Usuário não tem permissão para solicitar benefício <br/>** **[FE03] Usuário sem permissão para essa funcionalidade <br/>**|


## 5. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 24/08/2021 | 0.1 | Criação do Documento com tema, épico e história de usuário  | Rhuan Marques | Giulia Lobo |
| 07/09/2021 | 1.0 | Adição da nova versão do diagrama e finalização das tabelas de caso de uso  | Denniel William |  |
