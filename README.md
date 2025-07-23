# Simple Python Calculator

A basic Python program that performs arithmetic operations on two user-input numbers.

## Description

This Python script allows users to input two numbers and then calculates:
- Sum (addition)
- Difference (subtraction)
- Product (multiplication)
- Quotient (division)

The program includes error handling for division by zero.

## Features

- Handles both integer and decimal inputs
- Clean, user-friendly interface
- Protection against division by zero
- Formatted output of all results

## How to Use

1. Make sure you have Python installed on your system
2. Run the script using: `python calculator.py`
3. Follow the on-screen prompts:
   - Enter the first number
   - Enter the second number
4. View the calculated results

## Code Example

```python
# Get user input
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform calculations
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2

# Handle division carefully
if num2 != 0:
    quotient_result = num1 / num2
else:
    quotient_result = "undefined (cannot divide by zero)"

# Display results
print("\nResults:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
```

## Requirements

- Python 3.x

## Possible Improvements

Future versions could include:
- More operations (exponents, modulus, etc.)
- Continuous operation mode (keep calculating until user quits)
- Graphical user interface
- History of calculations

## Author

[Your Name]

## License

This project is open source and available under the [MIT License](LICENSE).
