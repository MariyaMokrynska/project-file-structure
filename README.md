# Project File Structure

## Overview

This project implements basic arithmetic operations (addition, subtraction, multiplication, and division) in Python. It includes unit tests to ensure the correctness of each operation using pytest.

## Setup Instructions

1. In GitHub, click on the "Fork" button and fork the repository https://github.com/AdaGold/project-file-structure to your GitHub account. This will make a copy of the project in your GitHub account.

2. Clone it with 

git clone ...

3. Create and Activate a Virtual Environment

python -m venv venv
source venv/bin/activate  

4. Install Dependencies

pip install -r requirements.txt

## Running the Application

Each arithmetic operation is implemented in its respective module inside src/. You can use these functions directly in your Python scripts.

Example usage:

from src.division import perform_operation
print(perform_operation(10, 2))  # Output: 5.0

## Running Tests

To ensure correctness, the project includes unit tests inside the tests/ directory. You can run all tests using:

pytest

Or run a specific test file:

pytest tests/test_subtraction.py

## License

This project is licensed under the terms of the LICENSE file.
