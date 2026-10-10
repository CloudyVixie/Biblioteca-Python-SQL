# Biblioteca em Python e SQL

Este projeto é um programa de terminal para cadastrar e consultar livros. Foi feito com Python, SQLite e InquirerPy, que cria menus de seleção no terminal.

## O que dá para fazer

- Adicionar livros
- Consultar todos os registros
- Buscar um livro pelo título
- Consultar livros por autor
- Atualizar informações de um livro
- Excluir registros

## Como instalar e executar

É necessário ter Python instalado. Instale a única dependência externa:

```bash
pip install InquirerPy
```

Depois, execute o programa na pasta do projeto:

```bash
python biblioteca.py
```

## Como o código funciona

O `biblioteca.py` usa `sqlite3` para executar comandos SQL e guardar os registros no arquivo local `biblioteca.db`. A biblioteca `os` ajuda a localizar esse arquivo junto ao script, e o InquirerPy apresenta as opções de navegação.

A tabela `livros` guarda o identificador, o título, o gênero, o ano e o autor de cada registro.

| Campo | Tipo usado no código |
| --- | --- |
| `id_livro` | `INTEGER PRIMARY KEY` |
| `titulo` | `VARCHAR(100)` |
| `genero` | `VARCHAR(100)` |
| `ano` | `VARCHAR(4)` |
| `autor` | `VARCHAR(100)` |

## Arquivos

- `biblioteca.py`: menus, consultas e operações com os livros.
- `biblioteca.db`: banco de dados local, criado ou utilizado pelo programa.
- `LICENSE`: termos de uso do projeto.

## Referências

- [Documentação do sqlite3](https://docs.python.org/3/library/sqlite3.html#tutorial)
- [Documentação do InquirerPy](https://inquirerpy.readthedocs.io/en/latest/)
- [Documentação do SQL no W3Schools](https://www.w3schools.com/sql/default.asp)
- [Documentação do módulo os no W3Schools](https://www.w3schools.com/python/ref_module_os.asp)

## Licença

Este projeto usa a licença MIT.
