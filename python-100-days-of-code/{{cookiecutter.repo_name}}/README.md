# {{cookiecutter.project_name}}

This is repo contains code that I generate while working on the [100 Days of Code](https://www.udemy.com/course/100-days-of-code/) udemy course for learning Python.

This repo covers the project for day XX of the course.

![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/{{cookiecutter.github_username}}/{{cookiecutter.repo_name}})
![GitHub](https://img.shields.io/github/license/{{cookiecutter.github_username}}/{{cookiecutter.repo_name}})

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

```sh
# Install dependencies
pipenv install --dev

# Setup pre-commit hooks
pipenv run pre-commit install -t pre-commit
```

## Usage

- `main.py`: Executable to launch the application.

## License

Distributed under the MIT License. See [LICENSE](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.repo_name}}/blob/master/LICENSE) for more information.
