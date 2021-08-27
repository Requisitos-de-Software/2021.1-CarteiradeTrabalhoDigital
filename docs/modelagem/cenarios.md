# Cenários

## 1. Introdução

O propósito desse documento é explicar a importância da utilização de cenários para ajudar na na elicitação de requisitos e o comportamento do seu produto. Tratando também de sua metodologia, como a descrição dos cenários que podem ser obtidos através dos requisitos elicitados através de algumas técnicas tratadas em outros documentos desse repositório 

## 2. Metodologia

Cenários é uma estratégia reconhecida para compreender as interações entre ambientes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo. Os cenários geralmente são estruturados com título, metas (ou objetivos), contexto, ator(es), recursos, exceções e episódios.

## 3. Cenários

### C01 - Cadastrar usuário tendo registro e carteira de trabalho física

- **Objetivo:** Cadastrar usuário de forma a obter as informações da carteira de trabalho pelo aplicativo
- **Contexto:** 
Local - Casa
Tempo - 1 a 5 minutos
Pré-condição: Possuir um registro e/ou carteira de trabalho física
- **Ator(es):** Trabalhador de carteira assinada
- **Recursos:** Internet, Aplicativo e Carteira de Trabalho Física
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um usuário sem qualquer registro no governo.
- **Episódios:** Usuário deseja migrar sua carteira física para a carteira digital, usuário perdeu sua carteira física e passou a utilizar a carteira digital.

### C02 - Cadastrar usuário não tendo registro e carteira de trabalho física

- **Objetivo:** Cadastrar usuário de forma a registrar e criar uma carteira de trabalho
- **Contexto:** 
Local - Casa
Tempo - 1 a 5 minutos
Pré-condição: Não possuir registro de uma carteira de trabalho
- **Ator(es):** Usuário que deseja fazer uma carteira de trabalho
- **Recursos:** Internet, Aplicativo e Documento de identificação
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um usuário sem qualquer registro no governo.
- **Episódios:** Usuário deseja criar uma carteira de trabalho, usuário acaba de ingressar no mercado de trabalho e precisa criar uma carteira de trabalho.

### C03 - Realizar login

- **Objetivo:** Realizar login para acessar as informações da carteira de trabalho
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário que possui registro na carteira de trabalho digital
- **Recursos:** Internet, Aplicativo e Registro
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um usuário sem registro no aplicativo.
- **Episódios:** Usuário deseja acessar sua carteira de trabalho

### C04 - Realizar logout

- **Objetivo:** Realizar logout para desvincular a conta do dispositivo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário que possui registro na carteira de trabalho digital
- **Recursos:** Internet, Aplicativo e Registro
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um usuário sem conta no aplicativo.
- **Episódios:** Usuário deseja sair da sua conta para outra pessoa conseguir acessar sua conta pelo mesmo dispositivo, usuário deseja sair da conta por segurança para ninguém conseguir acessar suas informações.

### C05 - Registro de trabalho

- **Objetivos:** Acessar os registros de trabalho pelo aplicativo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Trabalhador com carteira assinada, desempregado
- **Recursos:** Ter vinculado a carteira de trabalho ao menos um registro de trabalho, aplicativo
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, não possuir registro de trabalho na carteira de trabalho.
- **Episódios:** Usuário deseja visualizar os registros de trabalho anteriores como também os antigos registrados em sua carteira de trabalho.

### C06 - Solicitar Ajuda

- **Objetivos:** Solicitar ajuda para o caso de qualquer dúvida no processo da carteira de trabalho digital como também do uso do aplicativo ****
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com dúvida em algum processo da carteira de trabalho ou funcionalidade do aplicativo.
- **Recursos:** Aplicativo, Conta e Internet.
- **Exceções:** Não possuir conta registrada, não ter dúvidas em algum processo ou funcionalidade do aplicativo
- **Episódios:** Usuário possui dificuldade com as funcionalidades do aplicativo, usuário possui dificuldade com os processos que envolvem a carteira de trabalho.

### C07 - Emissão da carteira de trabalho em pdf

- **Objetivos:** Emitir informações contratuais da carteira de trabalho digital em formato pdf
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário que deseja emitir informações contratuais para envio
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir necessidade de gerar informações da carteira de trabalho, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário precisa passar informações da sua carteira de trabalho para registro de um novo trabalho, usuário precisa gerar documento para comprovar tempo de trabalho ou experiência de trabalho

### C08 - Visualizar contratos

- **Objetivos:** Visualizar contratos atuais como anteriores do usuário que estão registrados na carteira de trabalho
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com contratos registrados na carteira de trabalho
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir contratos registrados na carteira de trabalho, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário deseja visualizar contratos anteriores para checar sua experiência de mercado

### C09 - Visualizar informações do usuário

- **Objetivos:** Visualizar informações cadastradas do usuário
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com conta cadastrada
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir conta registrada no aplicativo
- **Episódios:** Usuário deseja visualizar informações passadas durante o cadastro de conta, usuário deseja checar informações pertinentes da sua carteira de trabalho, usuário deseja checar validez das informações em sua carteira de trabalho digital

### C10 - Reportar divergência da informação no contrato

- **Objetivos:** Reportar divergências no contrato caso o usuário encontre alguma
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário que notou divergência no contrato
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Não possuir divergência em qualquer contrato registrado ou mostrado no aplicativo, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário nota divergência no seu contrato vigente e reporta para alteração, usuário nota divergência em seu contrato passado, e possui comprovante de informação equivocada e reporta divergência.

### C11 - Visualizar anotações no contrato

- **Objetivos:** Visualizar anotações feitas no contrato do usuário pela empresa
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com anotações feitas no contrato atual, como em anteriores
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir anotações no contrato, não possuir contratos associados a carteira de trabalho, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário consegue checar quais foram as anotações feitas no seu contrato em caso de falta, de licença médica ou férias

### C12 - Visualizar gráficos do contrato

- **Objetivos:** Visualizar gráficos relacionados ao contrato do usuário
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com contratos registrados na carteira de trabalho
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Não possuir contratos registrados na carteira de trabalho, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário deseja visualizar num formato mais simples de comparação as informações do seu contrato passado com o atual

### C13 - Solicitar seguro-desemprego

- **Objetivos:** Solicitar seguro-desemprego através do aplicativo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário permissão para solicitar seguro-desemprego
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Usuário sem permissão para o benefício do seguro-desemprego, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário deseja solicitar o seguro-desemprego após passar por dificuldades e estar desempregado

### C14 - Visualizar notificações

- **Objetivos:** Visualizar notificações de registro de trabalho como anotações feitas no contrato
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com conta cadastrada
- **Recursos:** Aplicativo, Conta
- **Exceções:** Usuário não possuir conta no aplicativo, usuário não possuir o aplicativo
- **Episódios:** Usuário se esquece de atualizar suas informações e é lembrado por notificação, usuário consegue checar anotações feitas no seu contrato pois é notificado quando feita, usuário é notificado quando é feito o registro de trabalho em sua carteira digital

### C15 - Consultar benefícios

- **Objetivos:** Consultar benefícios do contrato de trabalho
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Usuário com contrato vigente
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Usuário que não possui benefícios associados ao contrato, usuário sem registro de carteira de trabalho
- **Episódios:** Usuário deseja checar os benefícios do seu contrato atual, usuário deseja checar os benefícios que possuia em seus contratos passados

## 4. Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

## 5. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 26/08/2021 | 1.0 | Criação do Documento, introdução, metodologia e cenários  | Denniel William | Rhuan Marques |
