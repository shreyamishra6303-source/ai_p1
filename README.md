# Prime Checker

A small Python program that checks whether an integer is prime.

## Requirements

- Python 3

No third-party packages are required.

## Run the program

Open a terminal in this folder and run:

```powershell
py prime_checker.py
```

Enter an integer when prompted. For example:

```text
Enter an integer: 17
17 is prime.
```

The program reports that numbers less than 2 are not prime and displays a
helpful message if the input is not a valid integer.

## How it works

The `is_prime` function handles values below 2 and even numbers directly, then
checks odd divisors up to the square root of the number. The script can also be
imported as a module to use this function:

```python
from prime_checker import is_prime

print(is_prime(17))  # True
```
