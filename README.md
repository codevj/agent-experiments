# agent-experiments

Experiments with Agents

## Pre-requisites

If your Python environment is below version 3.11, follow these steps:

### Ensure Python 3.11 is Installed

Use a Python version manager like `pyenv` to install Python 3.11 if it’s not already installed:

```sh
pyenv install 3.11.5
```

### Switch to Python 3.11 for the Project

Use Poetry’s `env use` command to specify the correct Python executable for your project:

```sh
poetry env use ~/.pyenv/versions/3.11.5/bin/python
```

Replace `~/.pyenv/versions/3.11.5/bin/python` with the path to the Python 3.11 executable installed via `pyenv` or another version manager.

### Verify the Python Version in Poetry

After setting the environment, confirm the Python version Poetry is using:

```sh
poetry run python --version
```

### Install Dependencies

Now that the correct Python version is configured, you can run:

```sh
poetry install
```
