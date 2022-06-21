
# Cookiecutter template for your Cloudformation Rest API Python project!

Example project: https://github.com/francomor/example-cookiecutter-fast-api-aws


It includes:

* [AWS CloudFormation](https://aws.amazon.com/es/cloudformation/)
* [FastAPI](https://fastapi.tiangolo.com/)
* [Bitbucket pipelines](https://bitbucket.org/product/es/features/pipelines)
* [Lambda Powertools](https://github.com/awslabs/aws-lambda-powertools-python)
* [editor config](http://editorconfig.org)
* [poetry](https://python-poetry.org/)
* [pre-commit](https://pre-commit.com/)
* [isort](https://pycqa.github.io/isort/)
* [flake8](https://flake8.pycqa.org/en/latest/)
* [mypy](http://mypy-lang.org/)
* [cfn-lint](https://github.com/aws-cloudformation/cfn-lint)
* [Docker Compose](https://docs.docker.com/compose/)
* [sqlalchemy](https://www.sqlalchemy.org/)
* [alembic](https://alembic.sqlalchemy.org/en/latest/)
* [pytest](https://docs.pytest.org/en/7.1.x/)

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher):

```bash
pip install -U cookiecutter
```

Generate a Python project:

```bash
cookiecutter gh:francomor/cookiecutter-fast-api-aws
```

Variables:

* `project_name`: Name of the project
* `project_slug`: Auto generated based on `project_name`
* `project_short_description`: A short description of the project
* `business_owner_email`: name.surname@gmail.com

Then:

* Create a repo and put it there.
* Follow the setup instruction in the Readme file
