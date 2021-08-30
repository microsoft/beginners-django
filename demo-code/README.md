# ReleCloud sample

This is a sample Django project used for [Beginner's Series: Django](https://aka.ms/BeginnersSeriesDjango). It's a fictitious company offering tours to space.

## Install and startup steps

1. Clone the repository

    ```bash
    git clone https://github.com/microsoft/beginners-django
    cd beginners-django/demo-code
    ```

1. Install the prerequisites

    ```bash
    # Linux/macOS/BASH
    python3 -m venv venv
    source ./venv/bin/activate
    pip install -r requirements.txt

    # Windows
    python -m venv venv
    .\\venv\\scripts\\activate
    pip install -r requirements.txt
    ```

1. Open the project in Visual Studio Code

    ```bash
    code .
    ```

## SQLite database

For this sample, the SQLite database is included. Typically this would be ignored in the .gitignore file. To ensure a working site with data was provided, the starting database is included.
