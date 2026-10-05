# PLP Python Week 6

This repository contains my Week 6 Python assignment on handling errors with `try` and `except`.

* `safe_tools.py` — Contains three safe functions for division, number conversion, and dictionary field lookup.
* `unbreakable.py` — Contains the error-handling practice for Question 2.

The `if` check cannot catch `"abc"` on its own because checking whether text is numeric and converting text with `int()` are different operations. `int("abc")` raises a `ValueError`, so `try/except` is needed to safely handle the error.
