# 📚 Biblioteca-Python-SQL

> Um sistema simples de gerenciamento de livros desenvolvido para praticar **Python + SQL**.

---

## 🛠️ Tecnologias

* 🐍 **Python**
* 🗃️ **SQLite**
* ⌨️ **InquirerPy**

---

## 📌 Funcionalidades

* ➕ Adicionar livros
* 🔎 Consultar livros
* 📖 Consultar um registro específico
* ✏️ Atualizar informações
* 🗑️ Deletar livros

---

## 📦 Bibliotecas utilizadas

O projeto utiliza os seguintes módulos:

### `sqlite3`

Módulo da biblioteca padrão do Python utilizado para criar a conexão com o banco de dados SQLite e executar as consultas SQL.

```python
import sqlite3
```

**Não é necessário instalar com `pip`.**

### `os`

Módulo da biblioteca padrão do Python utilizado no projeto para trabalhar com caminhos de arquivos e limpar o terminal.

```python
import os
```

**Não é necessário instalar com `pip`.**

### `InquirerPy`

Biblioteca externa utilizada para criar os menus interativos do sistema.

```python
from InquirerPy import prompt
```

Para instalar:

```bash
pip install InquirerPy
```

---

## 💻 Instalação

Depois de clonar o repositório, instale a única dependência externa:

```bash
pip install InquirerPy
```

Depois, execute:

```bash
python biblioteca.py
```

O arquivo `biblioteca.db` será utilizado para armazenar os dados do sistema.

---

## 🗄️ Banco de dados

O projeto utiliza **SQLite** para armazenar os registros dos livros.

### Tabela `livros`

| Campo      | Descrição              |
| ---------- | ---------------------- |
| `id_livro` | Identificador do livro |
| `titulo`   | Título do livro        |
| `genero`   | Gênero literário       |
| `ano`      | Ano de publicação      |
| `autor`    | Autor do livro         |

---

## 📁 Estrutura

```text
Biblioteca-Python-SQL/
├── biblioteca.py
├── biblioteca.db
└── README.md
```

---

## 🎯 Objetivo

Este projeto foi desenvolvido como parte dos estudos de **Python e SQL**, colocando em prática conceitos como:

* Funções
* Listas e tuplas
* CRUD
* Consultas SQL
* Parâmetros em consultas
* Integração entre Python e SQLite
* Uso de banco de dados

O projeto ainda está em desenvolvimento e poderá receber novas funcionalidades e melhorias futuramente.

---

## 📚 Documentação e referências

### Python

* 🐍 [Documentação oficial — `sqlite3`](https://docs.python.org/3/library/sqlite3.html#tutorial)
* 🗂️ [Python Academy — Biblioteca `os`](https://pythonacademy.com.br/blog/a-biblioteca-os-do-python)
* 🗂️ [W3Schools — Python `os` Module](https://www.w3schools.com/python/ref_module_os.asp)
* 📋 [W3Schools — Python Lists](https://www.w3schools.com/python/python_lists.asp)

### SQL

* 🗃️ [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/default.asp)

### InquirerPy

* ⌨️ [Documentação oficial — InquirerPy](https://inquirerpy.readthedocs.io/en/latest/)

---

### 📚 Projeto de estudo

Desenvolvido por **Vixie**.
