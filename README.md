# 📚 Biblioteca-Python-SQL

Um sistema simples para cadastrar e gerenciar livros usando Python, SQLite e InquirerPy.

---

## 🛠️ Tecnologias

- Python
- SQLite
- InquirerPy

O projeto usa `sqlite3` e `os`, que já fazem parte do Python.

A única biblioteca externa usada é o InquirerPy.

### Instalação

```bash
pip install InquirerPy
```

Para iniciar:

```bash
python biblioteca.py
```

---

## 📌 Funcionalidades

- Adicionar livros
- Consultar livros
- Consultar um livro pelo registro
- Atualizar dados
- Excluir livros

---

## 🗄️ Banco de dados

O SQLite guarda os dados dos livros em um arquivo local.

| Campo | Tipo |
| --- | --- |
| `id_livro` | INTEGER |
| `titulo` | VARCHAR |
| `genero` | VARCHAR |
| `ano` | VARCHAR |
| `autor` | VARCHAR |

---

## 📁 Estrutura

```text
Biblioteca-Python-SQL/
├── biblioteca.py
├── biblioteca.db
├── LICENSE
└── README.md
```

---

## 📚 Referências

- [Documentação Python — sqlite3](https://docs.python.org/3/library/sqlite3.html#tutorial)
- [Python Academy — Biblioteca os](https://pythonacademy.com.br/blog/a-biblioteca-os-do-python)
- [W3Schools — Python os](https://www.w3schools.com/python/ref_module_os.asp)
- [W3Schools — Python Lists](https://www.w3schools.com/python/python_lists.asp)
- [W3Schools — SQL](https://www.w3schools.com/sql/default.asp)
- [Documentação InquirerPy](https://inquirerpy.readthedocs.io/en/latest/)

---

## 📄 Licença

Este projeto usa a licença MIT.
