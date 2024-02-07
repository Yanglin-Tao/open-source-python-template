# Open Source Python Template
This is an advanced template for designing and developing Python projects with CI/CD. This template serves as a foundation and includes features for build management, unit testing, continuous integration, static analysis, code style adherence, and component specification. 

The details of this template are listed below: 
The programming language: Python
Testing Framework: Pytest
Continuous Integration Solution: CircleCI
Static Analysis Tools: Ruff, Flake8, MyPy
Code Formatting Solution: TBD 
Package/Dependency Manager: PDM (Python Dependency Management)

## Initial Setup
Install PDM as package and dependency manager:

    pip install pdm

Install initial dependencies:

    pdm install --dev
To update dependencies, run the following:

    pdm update

## Using Features
To use mypy, run the following:

    pdm run mypy <filename>

To use ruff, run the following: 

    pdm run ruff <filename>

To use pytest, run the following:

    pdm run pytest tests/test_addition.py

To run the application, run the following: 

    pdm run src/main.py

## Contributors - Team Glaceon
- Yifei Zhuang
- Fan Yang
- Bowen Gong
- Yanglin Tao
- Winnie Zheng
- Kaining Mao
