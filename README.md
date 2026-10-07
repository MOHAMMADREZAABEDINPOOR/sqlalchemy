<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="SQLALCHEMY CRUD — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="learning / English and Persian documentation" />

</div>

# SQLALCHEMY CRUD

Four Python ORM exercises demonstrate insertion, selection, update and deletion against a MySQL table.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/sqlalchemy) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [Static artwork](assets/readme/hero.png)

## Features

- Mapped pr1 table
- Insert/select/update/delete scripts
- Session-based ORM operations

## Stack

| Tool | Version / source |
|---|---|
| Python | `standard library / source imports` |

## Getting started

Python 3; a desktop/Tk installation for Tkinter or turtle examples. Tkinter is provided by the Python installation, not pip. Legacy dependencies may need a compatible Python version.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/sqlalchemy.git
cd sqlalchemy

python -m pip install "SQLAlchemy<2" mysql-connector-python
python "sql insert.py"
python "sql1 select.py"
```

## Configuration

No standard environment template is defined. Standalone exercises need no external configuration; inspect any service constants or paths in the source before running.

## Usage

Create a disposable MySQL database, replace the development connection strings in all scripts, then explore insert/select before update/delete.

## Project structure

| Path | Role |
|---|---|
| [`assets/`](assets/) | Brand/media/README assets |
| [`sql insert.py`](sql%20insert.py) | Project entry/configuration file |
| [`sql1 select.py`](sql1%20select.py) | Project entry/configuration file |
| [`sql2 update.py`](sql2%20update.py) | Project entry/configuration file |
| [`sql3 delete.py`](sql3%20delete.py) | Project entry/configuration file |

## Commands and checks

No automated test command is declared in a manifest. Verify behavior through a local example run.

## Deployment

This is a local learning exercise, not a public service. Browser exercises can use static hosting.

## Limitations

Connection strings are hardcoded in the historical source. Update/delete expect matching rows and can fail if absent. Use a disposable database.

## Troubleshooting

- Connection failure: configure a running disposable MySQL database and replace the source connection strings.
- Update/delete failure: create the expected row before running those examples.

## Contributing

Create a focused branch, verify the affected behavior and explain the change clearly. Keep private data, build outputs and local databases out of commits.

## License

No repository-level license file is included in this snapshot. Public visibility alone does not grant reuse rights; contact the repository owner for terms.

---

Part of **PIMX** · Documentation in English and Persian.
