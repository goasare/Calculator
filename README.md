# Calculator

A simple calculator project written in Python.

## Features

The `Calc` class provides the following methods:

- **add** — adds two numbers
- **sub** — subtracts two numbers
- **mul** — multiplies two numbers
- **div** — divides two numbers
- **pow** — raises a number to a power
- **sqrt** — returns the square root of a number

## Usage

```python
from calc import Calc

calc = Calc()
print(calc.add(2, 3))   # 5
print(calc.sqrt(16))    # 4.0
```

## Style

Code style is checked automatically with pycodestyle via GitHub Actions on every push.