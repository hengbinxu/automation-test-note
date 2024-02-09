# Automation Documentation

## How to setup the project?

- Setup by `venv`

    ```shell
    # Create a virtual environment
    python -m venv .venv

    # Activate the virtual environment
    source .venv/bin/activate

    # Upgrade pip
    pip install --upgrade pip

    # Install required packages
    pip install -r requirements.txt
    ```

- Setup by `Poetry`

    ```shell
    # Create a virtual environment
    poetry env use python

    # Install required packages
    poetry install --with dev --no-root
    ```

## How to start the server?

```shell
mkdocs serve
```
