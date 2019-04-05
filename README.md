# python-template

[![Build Status](https://travis-ci.com/FriesischScott/python-template.svg?branch=master)](https://travis-ci.com/FriesischScott/python-template)

This is a basic setup for any new python 3 project. It uses `autopep8` for auto-formatting, `flake8` for linting and `pytest` for testing.

## Installation

To get started, create and activate a new virtual environment.

```
python -m venv .venv
source .venv/bin/activate
```

Next, install the dependencies.

```
pip install -r requirements.txt
```

Finally, install the pre-commit hooks.

```
pre-commit install
```
