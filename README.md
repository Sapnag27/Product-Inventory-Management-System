# Product Inventory Management System

## Python Practical 10 – Student Assignment

## Student Practical

**NAME** **:-** Sapna Gupta,
**ROLL NO** **:-**  07

### Project Description

The Product Inventory Management System is a Python application developed to manage basic product information and perform inventory operations.

This project demonstrates unit testing using pytest, logging using Python's logging module, and code quality checking using Ruff.

### Features

1. Calculate the total product price.
2. Apply percentage discounts.
3. Check available product stock.
4. Validate invalid inputs using exceptions.
5. Record application events and errors using logging.
6. Perform automated unit testing using pytest.
7. Check and format Python code using Ruff.

### Technologies Used

- Python
- pytest
- Python Logging Module
- Ruff
- Visual Studio Code

### Project Structure

```text
Product_Inventory_Management/
│
├── inventory.py
├── test_inventory.py
├── logging_demo.py
├── main.py
│
├── Screenshots/
│   └── pratical-10(1).png
├── requirements.txt
├── README.md
├── .gitignore
└── .venv/
```

### Installation and Setup

Create a virtual environment:

```bash
python3 -m venv .venv
```

Activate it on zShell:

```zsh or bash
source .venv/bin/activate```


### Execute the Application

```bash
python3 main.py
```

### Run Unit Tests

```bash
python3 -m pytest -v
```

### Run Logging Demonstration

```bash
python3 logging_demo.py
```

The application creates an `application.log` file containing timestamps, log levels, successful operations, warnings and errors.

### Ruff Code Quality Checks

Check Python code:

```bash
python3 -m ruff check .
```

Apply automatic fixes:

```bash
python3 -m ruff check . --fix
```

Format Python files:

```bash
python3 -m ruff format .
```

Verify formatting:

```bash
python -m ruff format --check .
```


# Screenshots and Practical Output

The following screenshots show the execution and output of Python Practical 09.

### Screenshot 1 – Practical Execution

![Practical 10A Screenshot](Screenshots/pratical(10A)-1.png)

**Image Path:**
`Screenshots\pratical-10(1).png`

### Screenshot 2 – Practical Execution

![Practical 10A Screenshot](Screenshots/pratical(10A)-2.png)

**Image Path:**
`Screenshots\pratical-10(2).png`

### Screenshot 3 – Practical Execution
![Practical 10A Screenshot](Screenshots/pratical(10A)-3.png)

**Image Path:**
`Screenshots\pratical-10(3).png`

### Screenshot 4 – Practical Execution

![Practical 10A Screenshot](Screenshots/pratical(10A)-4.png)

**Image Path:**
`Screenshots\pratical-10(4).png`

### Screenshot 5 – Practical Execution

![Practical 10A Screenshot](Screenshots/pratical(10A)-5.png)

**Image Path:**
`Screenshots\pratical-10(5).png`


---


### Functions Implemented

| Function | Description |
|---|---|
| calculate_total_price() | Calculates total product cost |
| apply_discount() | Applies percentage discount |
| check_stock() | Checks product availability |

### Testing

The project includes automated test cases for:

- Valid product prices and quantities.
- Decimal prices.
- Discount calculations.
- Zero and full discounts.
- Invalid discounts.
- Available and insufficient stock.
- Negative values.
- Invalid input types.

### Logging

The application uses Python's logging module to record application events, successful operations, warnings and errors.

### Conclusion

This practical demonstrates how unit testing, logging and code-quality tools can be used together to develop reliable, readable and maintainable Python applications.
