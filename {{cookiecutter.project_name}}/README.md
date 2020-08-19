
* TODO: Add codecov token to `.travis.yml`

[![Build status](https://travis-ci.com/{{cookiecutter.github_project_name}}.svg?branch=master)](https://travis-ci.com/{{cookiecutter.github_project_name}}?branch=master)
[![codecov](https://codecov.io/gh/{{cookiecutter.github_project_name}}/branch/master/graph/badge.svg)](https://codecov.io/gh/{{cookiecutter.github_project_name}})

# Project Setup

Setup a python virtual environment and install all dependencies. The following instructions are for poetry (my preferred dependency and virtual environment manager)

1. Create virtual environment and install all dependencies: `poetry install`
2. Spawn a shell within your virtual environment: `poetry shell`

# Contributing

Run `make precommit` before commiting.
