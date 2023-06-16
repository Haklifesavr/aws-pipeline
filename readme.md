# Data Pipeline with Python and PostgreSQL

This project showcases a straightforward data pipeline that fetches data from an API, inserts the data into a PostgreSQL database, and verifies the data. The pipeline is built using Python, and specifically makes use of the `requests` and `psycopg2` libraries.

## Requirements

Before you begin, please make sure that you have the following installed:

- Python 3.6 or higher
- PostgreSQL server

## Getting Started

1. Clone this repository:

   
   git clone <repository_url>

2. Initializing a virtual environment:

    ```bash
    python -m venv .venv

3. Activating the virtual environment:

* For Windows
    ```bash
    cd .venv/scripts
    .\activate

* For MacOS
    ```bash
    source .venv/bin/activate

4. Activating the virtual environment:

    ```bash
    cd .venv/scripts
    .\activate

5. Installing requirements:

    ```bash
    pip install -r requirements.txt

6. Running the main pipeline:

    ```bash
    python main.py

7. Running the unit tests:

    ```bash
    python -m unittest discover -s . -p "*tests.py"

8. Running the entire project at once:
* For Windows:
    ```bash
    .\run.bat

* For MacOS:
    ```bash
    chmod +x run.sh
    ./run.sh