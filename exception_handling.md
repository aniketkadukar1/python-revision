# Python Exception Handling Quick Revision

## 1. What is Exception Handling?
- **Exception Handling** is a mechanism in Python to handle errors during the execution of a program, ensuring the program doesn't crash unexpectedly.
- Exceptions are raised when the interpreter encounters errors, such as trying to divide by zero or accessing a variable that doesn't exist.

## 2. Common Python Exceptions:
- **`ZeroDivisionError`**: Division by zero.
- **`IndexError`**: List index out of range.
- **`KeyError`**: Accessing a key not found in a dictionary.
- **`ValueError`**: Passing the wrong type of argument to a function.
- **`TypeError`**: Unsupported operation between types.
- **`FileNotFoundError`**: File not found in the specified location.
- **`NameError`**: Variable not defined.

## 3. Basic Syntax of Exception Handling
The `try` block lets you test a block of code for errors, the `except` block allows you to handle the error, and the `finally` block lets you execute code regardless of the result.

```python
try:
    # Code that might raise an exception
    result = 10 / 0
except ZeroDivisionError:
    # Handling the exception
    print("Cannot divide by zero!")
finally:
    # Code that runs no matter what
    print("Execution complete.")
```

### output
```python
Cannot divide by zero!
Execution complete.
```
## 4. try, except, else, and finally Blocks
try: Code that might raise an exception.
except: Code to handle exceptions.
else: Executes if no exceptions occur.
finally: Always executes, whether there’s an exception or not.

```python
try:
    number = int(input("Enter a number: "))
except ValueError:
    print("That's not a valid number!")
else:
    print(f"Success, you entered {number}.")
finally:
    print("This will always be executed.")
```
### output
