# Notes

## Template References

- https://github.com/joaopalmeiro/template-python-script
- https://github.com/pyenv/pyenv-virtualenv
- https://github.com/guludo/venv-run
- https://docs.python.org/3.10/library/venv.html#how-venvs-work
- https://www.packtpub.com/product/building-data-science-applications-with-fastapi-second-edition/9781837632749
- https://github.com/PacktPublishing/Building-Data-Science-Applications-with-FastAPI-Second-Edition
- https://github.com/python/cpython/issues/83758
- https://pip.pypa.io/en/stable/installation/#upgrading-pip
- https://pip.pypa.io/en/stable/cli/pip_install/#examples
- `require-virtualenv`:
  - https://pip.pypa.io/en/stable/cli/pip/#cmdoption-require-virtualenv
  - https://unix.stackexchange.com/questions/492041/is-there-a-way-to-disable-pip-outside-of-a-virtual-environment
  - https://pip.pypa.io/en/stable/cli/pip_config/: "with the special prefix `global` affecting any command"
  - https://pip.pypa.io/en/stable/topics/configuration/#boolean-options: `no-cache-dir = false`

### Commands

```bash
python -m venv --clear --prompt template-python-venv-script venv
```

```bash
python -m pip install --upgrade pip
```

## Commands

```bash
python -m venv --help
```

```bash
deactivate && rm -rf venv
```
