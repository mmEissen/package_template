# Just Another Python Package Template

Autoformat with black, lint with flake8, typecheck with mypy, manage dependencies with poetry, test with pytest, automate with tox

## Requirements

- Python 3.8
- poetry

## Commands

| Install (creates `.venv`) | `poetry install`                              |
|---------------------------|-----------------------------------------------|
| Run all CI steps          | `poetry run tox`                              |
| Run tests/lint/typing     | `poetry run tox -e lint -e typecheck -e test` |
| Install Extras            | `poetry install -E lint -E typecheck -E test` |

Installing extras makes them available in your local `.venv`. This allows vscode to find the necessary commands for editor integration.
