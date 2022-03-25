# Exercise 1 - Full stack open part11

Language of choice: Python

## Python equivalent of linting, testing, and building

Linters in Python can be broadly divided into 2 categories:

- Logical lint (code errors, code with potentially unintended results, dangerous code patterns). Some of the Python linters that fall into this category are pycodestyle, pydocstyle.

- Stylistic lint (code not conforming to defined conventions). Some of the Python linters that fall into this category are PyFlakes, Bandit, and MyPy.

Pylint is a Python linter that is both logical and stylistic.

Also, some linters are just multiple linters packaged nicely together. For example: Flake8, Pylama.

Python does come with a built-in testing module: unittest. It provides a solid base for writing test suites but has a few shortcomings. A popular testing framework that attempts to tackle these issues is pytest.

Building: Since Python is an interpreted language, there is no need for a build step.

## Alternatives to Jenkins and GitHub Actions

Some of the popular alternatives to Jenkins and GitHub Actions are CircleCI, TravisCI, CodeShip, and Semaphore.

## Self-hosted vs. cloud-based environment

Given the setup of one six-person team and presumably a project that does not require tons of resources, the cloud-based setup seems like a reasonable choice.
