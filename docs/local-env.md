# Build locally

1. Install [Poetry](https://python-poetry.org/docs/):
    ```
    curl -sSL https://install.python-poetry.org | python3 -
    ```
2. To activate virtual env:
    ```
    poetry shell
    ```
3. To install dependencies:
    ```
    poetry install
    ```
4. To run unit tests:
    ```
    make test
    ```
5. To format code style using black:
    ```
    make format
    ```
