# Boilerplate

> black, isort and mypy(strict) environments.

## How do use it?

If you already have [Poetry](https://python-poetry.org/) installed locally, you can install the dependencies using the following command:

```sh
poetry install
```

### Using virtual environments

First, create a virtual environment using the following command.

```sh
python -m venv .venv
```

Activate the virtual environment.

```sh
# Windows
.venv/Scripts/Activate.ps1

# Linux/macOS
.venv/bin/Activate.ps1 
```

After activation is complete, install Poetry in the virtual environment using the following command.

```sh
# Windows
.venv/Scripts/pip install -U pip setuptools
.venv/Scripts/pip install poetry

# Linux/macOS
.venv/bin/pip install -U pip setuptools
.venv/bin/pip install poetry
```

Install dependencies.

```sh
poetry install
```

## Support commands

### ``poetry run black``

### ``poetry run isort``

### ``poetry run mypy``

### ``poetry run pytest``
