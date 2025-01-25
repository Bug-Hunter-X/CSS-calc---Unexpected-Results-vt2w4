# CSS calc() Unexpected Results

This repository demonstrates a common issue with the `calc()` function in CSS.  The `calc()` function is powerful, but its behavior can be unexpected if you don't understand operator precedence and unit handling.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` file shows how to fix it.

**Problem:** Incorrect operator precedence in `calc()` can lead to unexpected results.

**Solution:** Ensure correct operator precedence using parentheses to clarify the order of operations.