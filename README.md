# calcutils-derfeb

[![PyPI version](https://img.shields.io/pypi/v/calcutils-derfeb.svg)](https://pypi.org/project/calcutils-derfeb/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)

A lightweight, well-typed Python utility library providing essential arithmetic and statistical helper functions. Built as an educational Python package.

## 🚀 Installation

Install the package directly from **PyPI**:

```bash
pip install calcutils-derfeb
```

### TestPyPI

To install a development or sandbox version from **TestPyPI**:

```bash
pip install \
  --index-url https://test.pypi.org/simple/ \
  --extra-index-url https://pypi.org/simple/ \
  calcutils-derfeb
```

## 💡 Quick Start

Import the functions directly from `calcutils`:

```python
from calcutils import add, multiply, average

# Core arithmetic
print(add(10.5, 24.5))
# Output: 35.0

print(multiply(4, 5))
# Output: 20.0

# Statistical calculations
numbers = [10, 20, 30, 40, 50]

print(average(numbers))
# Output: 30.0
```

## 🛠️ API Reference

| Function   | Signature                               | Description                                                                           |
| ---------- | --------------------------------------- | ------------------------------------------------------------------------------------- |
| `add`      | `add(a: float, b: float) -> float`      | Returns the sum of two numbers.                                                       |
| `multiply` | `multiply(a: float, b: float) -> float` | Returns the product of two numbers.                                                   |
| `average`  | `average(numbers: list) -> float`       | Returns the arithmetic mean of a list of numbers. Returns `0.0` if the list is empty. |

## 🔧 Local Development

### 1. Clone the repository

```bash
git clone https://github.com/Der-Feb/calcutils.git
cd calcutils
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
```

Activate it:

**Linux/macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```powershell
.venv\Scripts\activate
```

### 3. Install the package in editable mode

```bash
pip install -e .
```

### 4. Build the distribution

Make sure the build package is installed:

```bash
pip install build
```

Then build the package:

```bash
python -m build
```

The generated distribution files will be placed in the `dist/` directory.

## 🧪 Testing

If the project contains tests, run them with:

```bash
python -m pytest
```

You can install pytest with:

```bash
pip install pytest
```

## 📦 Package Information

* **Package name:** `calcutils-derfeb`
* **Python:** `3.8+`
* **License:** MIT
* **Package type:** Python utility library

## 📜 Links

* **GitHub:** https://github.com/Der-Feb/calcutils
* **PyPI:** https://pypi.org/project/calcutils-derfeb/
* **License:** https://opensource.org/licenses/MIT

## 📄 License

This project is distributed under the **MIT License**.
