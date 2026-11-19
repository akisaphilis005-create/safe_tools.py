# Week 6 Assignment: Safe Functions

## Assignment Files

- **safe_tools.py:** Contains three functions: safe_divide(), safe_number(), and get_field(), using try and except to handle errors.

## Reflection

An if check alone cannot catch "abc" because Python must first convert the text into an integer using int(). When the text is not a valid number, Python raises a ValueError, which is handled using try and except.
