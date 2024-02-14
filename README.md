# template-python-venv-script

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Opinionated [Python](https://www.python.org/) + [venv](https://docs.python.org/3.10/library/venv.html) template for new scripts.

## Development

```bash
pyenv install && pyenv versions
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
pip install TODO
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
