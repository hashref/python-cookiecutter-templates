# Python Cookiecutter Templates

The repo contains the various [cookiecutter](https://github.com/audreyr/cookiecutter) templates that I use for jump-starting my various projects.

## Prerequisites

- Python3
- cookiecutter

```sh
pipenv install cookiecutter --user
```

## Templates

Below are the following templates...

### Sparse

A sparse template for general purpose projects that can be built from the ground up.

#### Features

- Formatting with [black](https://github.com/psf/black)
- Static typing with [mypy](http://mypy-lang.org/)
- Linting with [flake8](http://flake8.pycqa.org/en/latest/)
- Git hooks that run all the above with [pre-commit](https://pre-commit.com/)

#### Quick Start

```sh
cookiecutter https://github.com/hashref/python-cookiecutter-templates --directory sparse
pipenv install --dev
pre-commit install
```

### Python 100 Days of Code

Built from the sparse template, I use this to create projects for the udemy [100 Days of Code: The Complete Python Pro Bootcamp for 2022](https://www.udemy.com/course/100-days-of-code/) course. It's basically the `sparse` template with the standardized README.md file that I use for all these projects.

<!-- markdownlint-disable no-duplicate-heading -->

#### Features

<!-- markdownlint-enable no-duplicate-heading -->

- Formatting with [black](https://github.com/psf/black)
- Static typing with [mypy](http://mypy-lang.org/)
- Linting with [flake8](http://flake8.pycqa.org/en/latest/)
- Git hooks that run all the above with [pre-commit](https://pre-commit.com/)

<!-- markdownlint-disable no-duplicate-heading -->

#### Quick Start

<!-- markdownlint-enable no-duplicate-heading -->

```sh
cookiecutter https://github.com/hashref/python-cookiecutter-templates --directory python-100-days-of-code
pipenv install --dev
pre-commit install
```

## License

Distributed under the MIT License. See [LICENSE](https://github.com/hashref/python-cookiecutter-templates/blob/master/LICENSE) for more information.
