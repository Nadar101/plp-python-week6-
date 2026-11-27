
# Week 6 Assignment: Safe Functions

## Files
- safe_tools.py: Contains three safe functions using try and except.
- README.md: Describes the assignment and explains error handling.

## Question: Why can the if check not catch abc on its own?

An if check cannot catch "abc" because it is not a valid whole number.
The int() function raises a ValueError when converting "abc".
Using try and except allows the program to handle the error without crashing.
