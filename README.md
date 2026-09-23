# 📚 Biblioteca-Python-SQL

Sistema de gerenciamento de livros desenvolvido em **Python**, utilizando **SQLite** e **InquirerPy**.

---

## 🛠️ Tecnologias

* Python
* SQLite
* InquirerPy

### Imports

```python
import sqlite3
import os
from InquirerPy import prompt
```

`sqlite3` e `os` fazem parte da biblioteca padrão do Python.
O único pacote externo utilizado é o `InquirerPy`.

### Instalação

```bash
pip install InquirerPy
```

Para executar:

```bash
python biblioteca.py
```

---

## 📌 Funcionalidades

* Adicionar livros
* Consultar livros
* Consultar um registro específico
* Atualizar informações
* Deletar livros

---

## 🗄️ Banco de dados

O projeto utiliza SQLite para armazenar os livros.

| Campo      | Tipo    |
| ---------- | ------- |
| `id_livro` | INTEGER |
| `titulo`   | VARCHAR |
| `genero`   | VARCHAR |
| `ano`      | VARCHAR |
| `autor`    | VARCHAR |

---

## 📁 Estrutura

```text
Biblioteca-Python-SQL/
├── biblioteca.py
├── biblioteca.db
└── README.md
```

---

## 📚 Referências

### Documentação e materiais de estudo

* [Documentação Python — sqlite3](https://docs.python.org/3/library/sqlite3.html#tutorial)
* [Python Academy — Biblioteca os](https://pythonacademy.com.br/blog/a-biblioteca-os-do-python)
* [W3Schools — Python os](https://www.w3schools.com/python/ref_module_os.asp)
* [W3Schools — Python Lists](https://www.w3schools.com/python/python_lists.asp)
* [W3Schools — SQL](https://www.w3schools.com/sql/default.asp)
* [Documentação InquirerPy](https://inquirerpy.readthedocs.io/en/latest/)
* [Vídeo utilizado como apoio aos estudos — YouTube](https://www.youtube.com/watch?v=9W2JlNgqLd4)
