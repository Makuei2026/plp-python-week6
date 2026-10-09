# PLP Python Week 6 Assignment: Error & Exception Handling

## File Descriptions
- `safe_tools.py`: Contains three functions (`safe_divide`, `safe_number`, and `get_field`) wrapped in `try/except` blocks to safely handle division by zero, invalid string-to-integer conversions, and missing dictionary keys without crashing.

## Question Response
An `if` check cannot easily validate `"abc"` on its own because strings do not have a built-in method that directly predicts if `int()` will succeed on all arbitrary text. While methods like `.isdigit()` exist, attempting to parse non-numeric input into an integer directly raises a `ValueError` at runtime, which is best caught and handled using a `try/except` block.
