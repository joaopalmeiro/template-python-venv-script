# template-python-venv-script

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Opinionated [Python](https://www.python.org/) + [venv](https://docs.python.org/3.10/library/venv.html) template for new scripts.

## Getting Started

1. Go to or create the project folder.
2. Get the template files:

```bash
npx degit github:joaopalmeiro/template-python-venv-script
```

or

```bash
npx degit github:joaopalmeiro/template-python-venv-script --force
```

3. Search for `template-python-venv-script` and replace it with the project name.
4. Search for `Opinionated [Python](https://www.python.org/) + [venv](https://docs.python.org/3.10/library/venv.html) template for new scripts.` and replace it with the (short) project description.
5. Search for `João Palmeiro` and replace it with the author's name.
6. Open the [requirements.txt](requirements.txt) file and add the project-specific dependencies.
7. Delete the [TEMPLATE.md](TEMPLATE.md) file.
8. Delete the [`Getting Started`](#getting-started) section.

## Development

Install [pyenv](https://github.com/pyenv/pyenv) (if necessary).

```bash
pyenv install && pyenv versions
```

```bash
pip config set global.require-virtualenv true
```

```bash
pip config list
```

```bash
python -m venv --clear venv
```

```bash
source venv/bin/activate
```

```bash
python --version && pip --version
```

```bash
pip install -r requirements.txt
```

or

```bash
pip install --index-url https://pypi.org/simple -r requirements.txt
```

```bash
ruff check .
```

```bash
ruff check --fix .
```

```bash
ruff format .
```

```bash
python 01.py
```

```bash
deactivate
```
