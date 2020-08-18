
* TODO: Add codecov token to `.travis.yml`

[![Build status](https://travis-ci.com/{{cookiecutter.github_project_name}}.svg?branch=master)](https://travis-ci.com/{{cookiecutter.github_project_name}}?branch=master)
[![codecov](https://codecov.io/gh/{{cookiecutter.github_project_name}}/branch/master/graph/badge.svg)](https://codecov.io/gh/{{cookiecutter.github_project_name}})

# Project Setup

1. Create a Python 3.8 Poetry environment (or your favorite other means of creating a virtual environment): `poetry shell`.
2. `poetry install` or if not using Poetry `pip install -r requirements.txt`

# Contributing

Run `make precommit` before commiting.
