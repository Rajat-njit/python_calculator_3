# Python Command-Line Calculator

A robust **command-line calculator** built in Python that supports addition, subtraction, multiplication, and division.  
The project uses **best practices**, complete **unit testing**, **parameterized tests**, and **continuous integration** with GitHub Actions.

---

## Features

- **REPL Interface**: Continuously interact with the calculator until the user exits.
- **Arithmetic Operations**: Add, subtract, multiply, and divide numbers.
- **Input Validation**: Handles invalid inputs gracefully.
- **Error Handling**: Prevents division by zero and unknown operations.
- **Testing**: 
  - Unit tests with `pytest`.
  - Parameterized tests for multiple scenarios.
  - 100% test coverage enforced via CI.
- **CI/CD**: GitHub Actions automatically runs tests on every push or pull request.

---

## Setup Instructions

### 1. Clone the repository (or use SSH)
```bash
git clone git@github.com:your-username/python-calculator.git
cd python-calculator

2. Create a virtual environment

python -m venv venv
# Activate venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

How to Run the Calculator
python main.py


REPL Example:
Enter an operation (add, subtract, multiply, divide) and two numbers, or 'exit' to quit: add 2 3
Result: 5.0
Enter an operation ... : exit
Exiting calculator...

Run Tests
pytest --cov=app tests/

GitHub Actions

CI workflow runs tests and checks coverage on push or pull request to main.

Workflow file: .github/workflows/python-app.yml.

Author

Your Rajat Pednekar
NJIT – Python Programming Assignment