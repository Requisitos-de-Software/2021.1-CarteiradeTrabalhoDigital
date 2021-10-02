# Cenários

## 1. Introdução

O propósito desse documento é explicar a importância da utilização de cenários para ajudar na na elicitação de requisitos e o comportamento do seu produto. Tratando também de sua metodologia, como a descrição dos cenários que podem ser obtidos através dos requisitos elicitados através de algumas técnicas tratadas em outros documentos desse repositório 

* Participante: Denniel William

## 2. Metodologia

Cenários é uma estratégia reconhecida para compreender as interações entre ambientes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo. Os cenários geralmente são estruturados com título, metas (ou objetivos), contexto, ator(es), recursos, exceções e episódios.

## 3. Cenários

### C01 - Cadastrar usuário tendo registro e <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> física

- **Objetivo:** Cadastrar <a href="../lexicos#usuario">usuário</a> de forma a obter as informações da <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> pelo aplicativo
- **Contexto:**
Local - Casa
Tempo - 1 a 5 minutos
Pré-condição: Possuir um registro e/ou <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> física
- **Ator(es):** Trabalhador de carteira assinada
- **Recursos:** Internet, Aplicativo e <a href="../lexicos#carteiraDeTrabalho">Carteira de Trabalho</a> Física
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um <a href="../lexicos#usuario">usuário</a> sem qualquer registro no governo.
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja migrar sua carteira física para a carteira digital, <a href="../lexicos#usuario">usuário</a> perdeu sua carteira física e passou a utilizar a carteira digital.

### C02 - Cadastrar usuário não tendo registro e <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> física

- **Objetivo:** Cadastrar <a href="../lexicos#usuario">usuário</a> de forma a registrar e criar uma <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Contexto:** 
Local - Casa
Tempo - 1 a 5 minutos
Pré-condição: Não possuir registro de uma <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> que deseja fazer uma <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Recursos:** Internet, Aplicativo e Documento de identificação
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um <a href="../lexicos#usuario">usuário</a> sem qualquer registro no governo.
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja criar uma <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> acaba de ingressar no mercado de trabalho e precisa criar uma <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>.

### C03 - Realizar login

- **Objetivo:** Realizar login para acessar as informações da <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> que possui registro na <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de trabalho digital</a>
- **Recursos:** Internet, Aplicativo e Registro
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um <a href="../lexicos#usuario">usuário</a> sem registro no aplicativo.
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja acessar sua <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>

### C04 - Realizar logout

- **Objetivo:** Realizar logout para desvincular a conta do dispositivo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> que possui registro na <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de trabalho digital</a>
- **Recursos:** Internet, Aplicativo e Registro
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, ser um <a href="../lexicos#usuario">usuário</a> sem conta no aplicativo.
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja sair da sua conta para outra pessoa conseguir acessar sua conta pelo mesmo dispositivo, <a href="../lexicos#usuario">usuário</a> deseja sair da conta por segurança para ninguém conseguir acessar suas informações.

### C05 - Registro de trabalho

- **Objetivos:** Acessar os registros de trabalho pelo aplicativo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** Trabalhador com carteira assinada, desempregado
- **Recursos:** Ter vinculado a <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> ao menos um registro de trabalho, aplicativo
- **Exceções:** Não possuir aparelho que suporte aplicativos Android ou IOS, Sistema Indisponível, não possuir registro de trabalho na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>.
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja visualizar os registros de trabalho anteriores como também os antigos registrados em sua <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>.

### C06 - <a href="../casos-de-uso#solicitarAjuda">Solicitar Ajuda</a>

- **Objetivos:** Solicitar ajuda para o caso de qualquer dúvida no processo da <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de trabalho digital</a> como também do uso do aplicativo ****
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com dúvida em algum processo da <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> ou funcionalidade do aplicativo.
- **Recursos:** Aplicativo, Conta e Internet.
- **Exceções:** Não possuir conta registrada, não ter dúvidas em algum processo ou funcionalidade do aplicativo
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> possui dificuldade com as funcionalidades do aplicativo, <a href="../lexicos#usuario">usuário</a> possui dificuldade com os processos que envolvem a <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>.

### C07 - Emissão da <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> em pdf

- **Objetivos:** Emitir informações contratuais da <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de trabalho digital</a> em formato pdf
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> que deseja emitir informações contratuais para envio
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir necessidade de gerar informações da <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> precisa passar informações da sua <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a> para registro de um novo trabalho, <a href="../lexicos#usuario">usuário</a> precisa gerar documento para comprovar tempo de trabalho ou experiência de trabalho

### C08 - Visualizar <a href="../lexicos#contratos">contratos</a>

- **Objetivos:** Visualizar <a href="../lexicos#contratos">contratos</a> atuais como anteriores do <a href="../lexicos#usuario">usuário</a> que estão registrados na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com <a href="../lexicos#contratos">contratos</a> registrados na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir <a href="../lexicos#contratos">contratos</a> registrados na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja visualizar <a href="../lexicos#contratos">contratos</a> anteriores para checar sua experiência de mercado

### C09 - Visualizar informações do usuário

- **Objetivos:** Visualizar informações cadastradas do <a href="../lexicos#usuario">usuário</a>
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com conta cadastrada
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir conta registrada no aplicativo
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja visualizar informações passadas durante o cadastro de conta, <a href="../lexicos#usuario">usuário</a> deseja checar informações pertinentes da sua <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> deseja checar validez das informações em sua <a href="../lexicos#carteiraDeTrabalhoDigital">carteira de trabalho digital</a>

### C10 - Reportar <a href="../lexicos#divergenciasContrato">divergência da informação no contrato</a>

- **Objetivos:** Reportar <a href="../lexicos#divergenciasContrato">divergências no contrato</a> caso o <a href="../lexicos#usuario">usuário</a> encontre alguma
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> que notou <a href="../lexicos#divergenciasContrato">divergência no contrato</a>
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Não possuir divergência em qualquer <a href="../lexicos#contratos">contrato</a> registrado ou mostrado no aplicativo, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> nota divergência no seu <a href="../lexicos#contratos">contrato</a> vigente e reporta para alteração, <a href="../lexicos#usuario">usuário</a> nota divergência em seu <a href="../lexicos#contratos">contrato</a> passado, e possui comprovante de informação equivocada e reporta divergência.

### C11 - Visualizar anotações no <a href="../lexicos#contratos">contrato</a>

- **Objetivos:** Visualizar anotações feitas no <a href="../lexicos#contratos">contrato</a> do <a href="../lexicos#usuario">usuário</a> pela empresa
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com anotações feitas no <a href="../lexicos#contratos">contrato</a> atual, como em anteriores
- **Recursos:** Aplicativo, Conta
- **Exceções:** Não possuir anotações no <a href="../lexicos#contratos">contrato</a>, não possuir <a href="../lexicos#contratos">contratos</a> associados a <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> consegue checar quais foram as anotações feitas no seu <a href="../lexicos#contratos">contrato</a> em caso de falta, de licença médica ou férias

### C12 - Visualizar <a href="../lexicos#grafico">gráficos</a> do <a href="../lexicos#contratos">contrato</a>

- **Objetivos:** Visualizar <a href="../lexicos#grafico">gráficos</a> relacionados ao <a href="../lexicos#contratos">contrato</a> do <a href="../lexicos#usuario">usuário</a>
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com <a href="../lexicos#contratos">contratos</a> registrados na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** Não possuir <a href="../lexicos#contratos">contratos</a> registrados na <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja visualizar num formato mais simples de comparação as informações do seu <a href="../lexicos#contratos">contrato</a> passado com o atual

### C13 - Solicitar <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>

- **Objetivos:** Solicitar <a href="../lexicos#seguroDesemprego">seguro-desemprego</a> através do aplicativo
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> permissão para solicitar <a href="../lexicos#seguroDesemprego">seguro-desemprego</a>
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** <a href="../lexicos#usuario">Usuário</a> sem permissão para o <a href="../lexicos#beneficios">benefício</a> do seguro-desemprego, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja solicitar o <a href="../lexicos#seguroDesemprego">seguro-desemprego</a> após passar por dificuldades e estar desempregado

### C14 - Visualizar <a href="../lexicos#notificacoes">notificações</a>

- **Objetivos:** Visualizar <a href="../lexicos#notificacoes">notificações</a> de registro de trabalho como anotações feitas no <a href="../lexicos#contratos">contrato</a>
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com conta cadastrada
- **Recursos:** Aplicativo, Conta
- **Exceções:** <a href="../lexicos#usuario">Usuário</a> não possuir conta no aplicativo, <a href="../lexicos#usuario">usuário</a> não possuir o aplicativo
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> se esquece de atualizar suas informações e é lembrado por <a href="../lexicos#notificacoes">notificação</a>, <a href="../lexicos#usuario">usuário</a> consegue checar anotações feitas no seu <a href="../lexicos#contratos">contrato</a> pois é notificado quando feita, <a href="../lexicos#usuario">usuário</a> é notificado quando é feito o registro de trabalho em sua carteira digital

### C15 - Consultar <a href="../lexicos#beneficios">benefícios</a>

- **Objetivos:** Consultar <a href="../lexicos#beneficios">benefícios</a> do <a href="../lexicos#contratos">contrato</a> de trabalho
- **Contexto:** 
Local - Qualquer lugar
Tempo - 1 a 2 minutos
Pré-condição: Possuir conta registrada no aplicativo
- **Ator(es):** <a href="../lexicos#usuario">Usuário</a> com <a href="../lexicos#contratos">contrato</a> vigente
- **Recursos:** Aplicativo, Conta e Internet
- **Exceções:** <a href="../lexicos#usuario">Usuário</a> que não possui <a href="../lexicos#beneficios">benefícios</a> associados ao <a href="../lexicos#contratos">contrato</a>, <a href="../lexicos#usuario">usuário</a> sem registro de <a href="../lexicos#carteiraDeTrabalho">carteira de trabalho</a>
- **Episódios:** <a href="../lexicos#usuario">Usuário</a> deseja checar os <a href="../lexicos#beneficios">benefícios</a> do seu <a href="../lexicos#contratos">contrato</a> atual, <a href="../lexicos#usuario">usuário</a> deseja checar os <a href="../lexicos#beneficios">benefícios</a> que possuia em seus <a href="../lexicos#contratos">contratos</a> passados

## 4. Bibliografia

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

## 5. Versionamento

| Data       | Versão | Descrição            |         Autor           | Revisor |
|------------|-----|-------------------------|-------------------------|---------|
| 26/08/2021 | 1.0 | Criação do Documento, introdução, metodologia e cenários  | Denniel William | Rhuan Marques |
| 13/09/2021 | 1.1 | Linkagem dos cenários com os léxicos | Murilo Gomes | Giulia Lobo |
| 26/09/2021 | 1.1 | Rastreabilidade do projeto  | Liverson Paulo e Giulia Lobo | Murilo Gomes |