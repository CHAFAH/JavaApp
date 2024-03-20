# DevOps Masters Program Class of 2024A Web Application

This web application displays a webpage welcoming users to the DevOps Masters Program Class of 2024A and showcases the management team.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3:

    ```bash
    sudo apt update
    sudo apt install python3
    ```

- pip: The Python package installer (usually installed with Python)

    ```bash
    sudo apt install python3-pip
    ```

## Installation

To install the required dependencies, follow these steps:

1. Clone this repository to your Ubuntu server:

    ```bash
    git clone https://github.com/CHAFAH/JavaApp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd JavaApp
    ```

3. Set up a virtual environment to isolate dependencies (optional but recommended):

    ```bash
    sudo apt install python3-venv
    python3 -m venv venv
    ```

    Activate the virtual environment:

    ```bash
    source venv/bin/activate
    ```

4. Install Flask:

    ```bash
    pip install Flask
    ```

    This command will install Flask, the web framework used by the application.

5. Redirect to `requirements.txt`:

    ```bash
    cd ..
    ```

6. Install the required dependencies using pip:

    ```bash
    pip install -r JavaApp/requirements.txt
    ```

    This command will install all the necessary dependencies listed in the `requirements.txt` file.

## Generating requirements.txt

To generate the `requirements.txt` file, follow these steps:

1. Make sure you're in the project directory and your virtual environment is activated.

2. Install all the required dependencies using pip.

3. Once all dependencies are installed, generate the `requirements.txt` file using `pip freeze`:

    ```bash
    pip freeze > requirements.txt
    ```

    This command will create a `requirements.txt` file containing a list of all installed packages and their versions.

## Running the Application

To run the application on your Ubuntu server, follow these steps:

1. Make sure you're in the project directory.

2. Run the Flask application:

    ```bash
    python app.py
    ```

## Accessing the Application in the Browser

Once the application is running, open your web browser and go to:

