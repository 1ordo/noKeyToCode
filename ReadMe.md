# Project Setup

## Python Version
This project requires Python version **3.12.6**.

## Setting Up the Python Environment

1. **Install Python 3.12.6**:
    - Download and install Python 3.12.6 from the [official Python website](https://www.python.org/downloads/release/python-3126/).

2. **Create a Virtual Environment**:
    - Open a terminal or command prompt.
    - Navigate to the project directory.
    - Run the following command to create a virtual environment:
      ```sh
      python -m venv env
      ```

3. **Activate the Virtual Environment**:
    - On **Windows**:
      ```sh
      .\env\Scripts\activate
      ```
    - On **Linux/MacOS**:
      ```sh
      source env/bin/activate
      ```

4. **Install Required Packages**:
    - Ensure you are in the virtual environment.
    - Run the following command to install the required packages:
      ```sh
      pip install -r requirements.txt
      ```

## Running Setup Scripts

You can use the provided scripts to set up the environment:

- **For Linux**:
  ```sh
  ./run_linux.sh
  ```

- **For Windows**:
  ```sh
  .\run_windows.bat
  ```

These scripts will automate the setup process, including creating and activating the virtual environment and installing the required packages.

## Additional Notes

- Ensure that you have the necessary permissions to execute the scripts.
