# Python Console Calculator Script

A lightweight, console-based Python script that performs basic arithmetic operations on floating-point numbers.

## Description

This script provides a simple menu-driven interface in the terminal. It prompts the user to select one of four basic operations (addition, subtraction, multiplication, or division) and then asks for two numbers. It calculates the result and displays it formatted clearly.

The script runs inside an infinite loop, allowing the user to perform multiple calculations consecutively without restarting the program.

## Features

  * **Four Basic Operations:** Supports Addition, Subtraction, Multiplication, and Division.
  * **Floating-Point Support:** Handles decimal numbers (floats) for precise calculations.
  * **Input Validation (Basic):** Checks if the selected operation index is between 1 and 4.
  * **Continuous Execution:** Runs in a loop for rapid, repeated use.

## Prerequisites

  * Python 3.x installed on your system.

## How to Use

1.  Save the Python code into a file named `calculator.py` (or any preferred name).

2.  Open your terminal or command prompt.

3.  Navigate to the directory where you saved the file.

4.  Run the script using the following command:

    ```bash
    python calculator.py
    ```

5.  Follow the on-screen prompts to select an operation and enter your numbers.

## Example Interaction

```text
[1] Addition
[2] Subtraction
[3] Multiplication
[4] Division

Choose an operation to perform [1-4]: 1
Enter the value of x: 10.5
Enter the value of y: 4.2
Answer: 10.5 + 4.2 = 14.7

[1] Addition
[2] Subtraction
[3] Multiplication
[4] Division

Choose an operation to perform [1-4]: 4
Enter the value of x: 20
Enter the value of y: 5
Answer: 20.0 / 5.0 = 4.0
```

## Important Note on Exiting

The script runs in an infinite `while True:` loop. To exit the program, you must manually interrupt it in your terminal:

  * **Windows/Linux:** Press `Ctrl + C`
  * **macOS:** Press `Ctrl + C` (or sometimes `Cmd + .`)
