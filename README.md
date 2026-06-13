# 🚀 Como Executar o Arquivo SQL

## 1. Baixe ou clone o repositório

```bash
git clone <url-do-repositorio>
```

ou faça o download dos arquivos diretamente pelo GitHub.

---

## 2. Abra seu gerenciador de banco de dados

Você pode utilizar ferramentas como:

* MySQL Workbench
* DBeaver
* phpMyAdmin
* MariaDB

---

## 3. Crie um banco de dados

Exemplo:

```sql
CREATE DATABASE oscar;
```

Selecione o banco criado:

```sql
USE oscar;
```

---

## 4. Execute o arquivo SQL

Abra o arquivo `.sql` presente no repositório e execute todo o script.

O script irá criar e/ou popular as tabelas necessárias para a realização dos exercícios.

---

## 5. Verifique se os dados foram importados

Exemplo:

```sql
SELECT * FROM oscar_indicados LIMIT 10;
```

Se os registros forem exibidos, a importação foi realizada com sucesso.

---

## 6. Resolva os exercícios

Com a base carregada, execute as consultas SQL propostas no roteiro de exercícios para explorar os dados históricos do Oscar.
