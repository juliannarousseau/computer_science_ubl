# SQLite e SQL

## Conteúdo

- DBMS (Database Management System)
- RDBMS (Relational Database Management System)
- O que é SQL
- Exemplos básicos de SQL
- SQLite
- Vantagens do SQLite
- Desvantagens do SQLite

---

# Sistemas de Banco de Dados

## DBMS (Database Management System)

DBMS significa **Database Management System**, ou **Sistema de Gerenciamento de Banco de Dados**.

É um software responsável por:

- armazenar dados
- organizar dados
- permitir consultas
- manipular informações

Exemplos de DBMS:

- MongoDB
- Redis
- Cassandra

Nem todo DBMS é relacional.

---

## RDBMS (Relational Database Management System)

RDBMS significa **Relational Database Management System**, ou **Sistema Gerenciador de Banco de Dados Relacional**.

Esses sistemas organizam os dados em:

- tabelas
- linhas
- colunas

As tabelas podem possuir **relações entre si**.

Exemplos de RDBMS:

- SQLite
- MySQL
- PostgreSQL
- SQL Server
- Oracle

Esses bancos utilizam a linguagem **SQL** para manipulação de dados.

---

# SQL

## O que é SQL?

SQL significa: **Structured Query Language**. Ou seja: **Linguagem de Consulta Estruturada**

SQL é utilizada para:

- consultar dados
- inserir dados
- atualizar dados
- apagar dados
- criar estruturas no banco

A linguagem recebe o nome "estruturada" porque as consultas seguem **uma estrutura definida**.

SQL surgiu na **década de 1970** e seus fundamentos permanecem praticamente os mesmos até hoje.

Por isso é considerada uma linguagem **muito estável e relevante**.

---

## Estrutura básica de uma consulta SQL

Uma consulta típica possui a estrutura:

```sql
SELECT colunas
FROM tabela
WHERE condicao;
````

---

## Exemplo: selecionar dados

```sql
SELECT * FROM usuarios;
```

Esse comando retorna **todos os registros da tabela `usuarios`**.

---

## Exemplo: selecionar colunas específicas

```sql
SELECT nome, idade FROM usuarios;
```

Retorna apenas as colunas **nome** e **idade**.

---

## Exemplo: inserir dados

```sql
INSERT INTO usuarios (nome, idade)
VALUES ('Ana', 25);
```

Insere um novo registro na tabela.

---

## Exemplo: atualizar dados

```sql
UPDATE usuarios
SET idade = 26
WHERE nome = 'Ana';
```

Atualiza o valor de um registro existente.

---

## Exemplo: remover dados

```sql
DELETE FROM usuarios
WHERE nome = 'Ana';
```

Remove registros da tabela.

---

# SQLite

## O que é SQLite?

SQLite é um **banco de dados relacional leve** que utiliza **SQL** como linguagem de consulta. Uma característica importante é que **todo o banco de dados fica armazenado em um único arquivo**. Diferente de outros bancos de dados, ele **não precisa de servidor**.

Exemplo de outros bancos que precisam de servidor:

* MySQL
* PostgreSQL

SQLite é muito utilizado em aplicações locais ou embarcadas.

---

## Onde o SQLite é usado

SQLite está presente em diversos sistemas e aplicações.

Exemplos:

* Android
* iOS
* navegadores
* aplicações desktop
* ferramentas de desenvolvimento

Muitos dispositivos já possuem SQLite instalado por padrão.

---

## Vantagens do SQLite

O SQLite possui várias características que o tornam muito prático.

* **Não precisa de configuração**
* **Banco de dados é apenas um arquivo**
* **Rápido e estável**
* **Muito utilizado em aplicações locais**
* **Alta compatibilidade com SQL**

A sintaxe utilizada é aproximadamente **90% compatível** com bancos como:

* MySQL
* PostgreSQL

---

## Desvantagens do SQLite

Apesar das vantagens, SQLite possui algumas limitações.

* Não possui controle avançado de **usuários e permissões**
* Não foi projetado para **alto volume de escrita simultânea**
* O banco normalmente precisa estar **no mesmo ambiente do backend**

Por isso, sistemas com tráfego massivo — como **Netflix ou YouTube** — utilizam bancos distribuídos ou servidores dedicados.

---

## Criando tabelas no SQLite

Como SQLite utiliza SQL, os comandos são os mesmos usados em outros bancos relacionais.

Por convenção, comandos SQL costumam ser escritos em **letras maiúsculas**, embora não seja obrigatório.

---

### Exemplo de criação de tabela

```sql
CREATE TABLE cursos (
  id INTEGER PRIMARY KEY,
  nome TEXT,
  aulas INTEGER
);
```

Essa tabela possui três colunas:

* **id** → identificador único do curso
* **nome** → nome do curso
* **aulas** → quantidade de aulas

Cada linha da tabela representará **um curso armazenado no banco de dados**.

---

## Inserindo dados no SQLite

```sql
INSERT INTO cursos (nome, aulas)
VALUES ('Banco de Dados', 20);
```

---

## Consultando dados no SQLite

```sql
SELECT * FROM cursos;
```

Esse comando retorna **todos os cursos armazenados no banco**.

---

💡 **Uma observação didática importante para seu repositório**

Para quem está aprendendo, a hierarquia correta é:


```
Banco de dados
↓
DBMS / RDBMS
↓
SQL (linguagem)
↓
SQLite / MySQL / PostgreSQL (implementações)
```

Isso evita um erro muito comum de iniciantes:

> achar que **SQL = banco de dados**, quando na verdade **SQL é a linguagem**.
