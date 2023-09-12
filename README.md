# Escopo do Projeto: Landing Page de Currículo

## Objetivo

Criar uma landing page de currículo pessoal, hospedada na Amazon S3, que exiba informações armazenadas em um banco de dados MySQL. O back-end será implementado em Node.js usando Express e hospedado no AWS Lambda.

---

## Stack Tecnológica

### Front-end:

- **React**: Para criar a UI da landing page.

### Back-end:

- **Node.js**: Linguagem de programação.
- **Express.js**: Framework para criar a API.

### Infraestrutura:

- **Amazon S3**: Para hospedagem da landing page.
- **AWS Lambda**: Para executar o back-end.
- **AWS RDS (MySQL)**: Para armazenar os dados do currículo.

---

## Requisitos Funcionais

1. **Front-end**:
   - Renderização dinâmica da página, solicitando dados ao back-end.

2. **Back-end**:
   - APIs para buscar informações armazenadas no banco de dados.

3. **Banco de Dados (MySQL)**:
   - Tabelas correspondentes a cada seção do currículo.

---

## Estrutura de Dados

### Tabelas do Banco de Dados

1. **Dados Básicos**
    - Cada item (nome, cargo, empresa, etc.) será armazenado em uma linha diferente, cada uma com seu próprio ID.
    - id
    - campo (nome, cargo atual, etc.)
    - valor

2. **Páginas**
    - id
    - nome
    - url

3. **Principais Competências**
    - id
    - nome

4. **Idiomas**
    - id
    - nome
    - nível

5. **Conquistas**
    - id
    - nome

6. **Experiências**
    - id
    - empresa
    - cargo
    - início
    - fim
    - descrição

---

## Roadmap para o Estagiário

### Semana 1: Preparação

1. **JavaScript**: Estudar o básico da linguagem JavaScript.
   - URL para recursos: https://www.w3schools.com/js/

2. **AWS**: Entender o básico sobre Amazon Web Services (AWS).
   - URL para recursos: https://aws.amazon.com/pt/getting-started/

### Semana 2: Back-end

1. **Node.js**: Aprofundar em Node.js.
   - URL para recursos: https://nodejs.org/en/docs/

2. **Express.js**: Aprender sobre Express.js.
   - URL para recursos: https://expressjs.com/

3. **AWS Lambda**: Estudar como implementar o back-end no AWS Lambda.
   - URL para recursos: https://aws.amazon.com/pt/lambda/getting-started/

### Semana 3: Front-end

1. **React**: Estudar React e como criar componentes.
   - URL para recursos: https://reactjs.org/tutorial/tutorial.html

### Semana 4: Banco de Dados e Integração

1. **MySQL**: Estudar MySQL e como funciona o AWS RDS.
   - URL para recursos: https://dev.mysql.com/doc/
   - URL para recursos do AWS RDS: https://aws.amazon.com/pt/rds/

2. **Integração**: Começar a integrar todas as partes.

### Semana 5-6: Desenvolvimento e Testes

1. Desenvolvimento do projeto seguindo os requisitos.
2. Testes e ajustes.

---

## Entregáveis

1. Código-fonte do projeto.
2. Documentação detalhada.
3. Landing page de currículo ao vivo.

---

## Credenciais

As credenciais da AWS serão fornecidas e devem ser usadas apenas para fins deste projeto.
