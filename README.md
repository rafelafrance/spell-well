# spell-well ![CI](https://github.com/rafelafrance/spell-well/workflows/CI/badge.svg)
A simple spell checker.

Based off of symmetric deletes method from SeekStorm. MIT license.
https://seekstorm.com/blog/1000x-spelling-correction/

## Install

You will need GIT to clone this repository. You will also need to have Python3.11+ installed, as well as pip, a package manager for Python.
You can install the requirements into your python environment like so:

```zsh
git clone https://github.com/rafelafrance/spell-well.git
cd spell-well
make install
```

The `make install` will create a virtual environment in `.venv`, then it will install dependencies into this directory.

Every time you want to run any script in this repository you will need to activate the virtual environment.

```zsh
cd /path/to/spell-well
source .venv/bin/activate
```

## Tests

There are tests which you can run like so:

```zsh
make test
```
