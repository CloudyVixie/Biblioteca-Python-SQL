# Biblioteca em Python e SQL

Programa de terminal para cadastrar, consultar e editar livros. Fiz o projeto para praticar Python, consultas SQL e operações de CRUD usando SQLite.

## Funcionalidades

- Cadastrar livros.
- Consultar todos os registros.
- Buscar livros pelo título.
- Consultar livros por autor.
- Atualizar informações de um livro.
- Excluir registros.

## Como instalar e executar

É necessário ter Python instalado. Instale a dependência usada para criar os menus do terminal:

```bash
pip install InquirerPy
```

Depois, execute o programa na pasta do projeto:

```bash
python biblioteca.py
```

## Como o código funciona

O arquivo `biblioteca.py` usa `sqlite3` para executar comandos SQL e guardar os registros no banco local `biblioteca.db`. O módulo `os` ajuda a localizar o banco junto ao script, e o InquirerPy apresenta as opções de navegação no terminal.

A tabela `livros` guarda o identificador, título, gênero, ano e autor.

| Campo | Tipo usado no código |
| --- | --- |
| `id_livro` | `INTEGER PRIMARY KEY` |
| `titulo` | `VARCHAR(100)` |
| `genero` | `VARCHAR(100)` |
| `ano` | `VARCHAR(4)` |
| `autor` | `VARCHAR(100)` |

## Arquivos

- `biblioteca.py`: menus, consultas e operações com os livros.
- `biblioteca.db`: banco SQLite utilizado pelo programa.
- `LICENSE`: licença do projeto.

## Referências

- [Documentação do sqlite3](https://docs.python.org/3/library/sqlite3.html#tutorial)
- [Documentação do InquirerPy](https://inquirerpy.readthedocs.io/en/latest/)
- [Tutorial de SQL do W3Schools](https://www.w3schools.com/sql/default.asp)
- [Documentação do módulo os](https://docs.python.org/3/library/os.html)

## Licença

Este projeto está sob a licença MIT.
