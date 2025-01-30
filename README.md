# Conexão Java com Banco de Dados

Este repositório contém exemplos e anotações sobre como conectar a linguagem Java (utilizando o IntelliJ IDEA) a um banco de dados. O foco principal é demonstrar a integração entre Java e bancos de dados, utilizando o **JDBC (Java Database Connectivity)**, e como realizar operações básicas de CRUD (Create, Read, Update, Delete) e gerenciar transações.

---

## O que foi aprendido?

### 1. **Configuração do Ambiente**
   - Para conectar Java a um banco de dados, é necessário utilizar um **Java Connector** (também conhecido como driver JDBC). Esse conector permite que o Java se comunique com o banco de dados.
   - No caso do MySQL, o conector pode ser baixado e adicionado ao projeto como uma dependência.

### 2. **Operações Básicas com JDBC**
   - **Conexão com o Banco de Dados**: Aprender a estabelecer uma conexão utilizando `DriverManager.getConnection()`.
   - **CRUD**:
     - **Create (Inserção)**: Como adicionar novos registros ao banco de dados usando comandos SQL e o método `executeUpdate()`.
     - **Read (Leitura)**: Como recuperar dados do banco de dados utilizando `ResultSet` e exibi-los no console do IntelliJ.
     - **Update (Atualização)**: Como modificar registros existentes no banco de dados.
     - **Delete (Exclusão)**: Como remover registros do banco de dados.
   - **Execução de Queries**: Uso de `Statement` e `PreparedStatement` para executar consultas SQL.

### 3. **Transações**
   - Aprendi que as transações são essenciais para garantir a integridade dos dados. Elas permitem que um conjunto de operações seja tratado como uma única unidade de trabalho.
   - Se todas as etapas de uma transação forem bem-sucedidas, as alterações são confirmadas (`commit`). Caso contrário, as alterações são desfeitas (`rollback`).
   - Isso é especialmente útil em operações que envolvem múltiplas etapas, onde um erro em qualquer parte do processo pode comprometer a consistência dos dados.

---

## Tecnologias Utilizadas
- **Java**: Linguagem de programação principal.
- **IntelliJ IDEA**: Ambiente de desenvolvimento integrado (IDE).
- **MySQL**: Banco de dados utilizado nos exemplos.
- **JDBC**: API para conexão e execução de operações no banco de dados.

---

## Como Executar os Exemplos?

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/FrancescoSala/jdbc.git
   ```
