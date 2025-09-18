# Python Command-Line Calculator

A robust **command-line calculator** built in Python that supports addition, subtraction, multiplication, and division.  
The project follows **best practices**, includes **complete unit testing**, **parameterized tests**, and **continuous integration** with GitHub Actions.

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

### Clone the Repository
Clone the repository using SSH or HTTPS:
```bash
git clone git@github.com:your-username/python-calculator.git
cd python-calculator
```

### Create a Virtual Environment
Create and activate a virtual environment to manage dependencies:
```bash
python -m venv venv

# Activate venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate
```

### Install Dependencies
Install required Python packages:
```bash
pip install -r requirements.txt
```

---

## How to Run the Calculator
Run the command-line calculator:
```bash
python main.py
```

### REPL Example:
```
Enter an operation (add, subtract, multiply, divide) and two numbers, or 'exit' to quit: add 2 3
Result: 5.0
Enter an operation ... : exit
Exiting calculator...
```

---

## Run Tests
Run all tests and check code coverage:
```bash
pytest --cov=app tests/
```

- Ensures **100% test coverage** as required.  
- Test files: `tests/test_operations.py` and `tests/test_calculator.py`.

---

## GitHub Actions

- CI workflow automatically runs tests and checks coverage on **push** or **pull request** to `main`.  
- Workflow file location: `.github/workflows/python-app.yml`.

---

## Project Structure

```
python-calculator/
│
├─ app/
│  ├─ calculator/
│  │  └─ __init__.py
│  └─ operations/
│     └─ __init__.py
│
├─ tests/
│  ├─ test_calculator.py
│  └─ test_operations.py
│
├─ main.py
├─ requirements.txt
└─ README.md
```

---

## Author

**Rajat Pednekar**  
NJIT – Python Programming Assignment
