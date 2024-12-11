# CSS `calc()` Errors

This repository demonstrates common and uncommon errors encountered when using the `calc()` function in CSS.  The `bug.css` file shows examples of incorrect usage, including issues with flexbox context, unit mismatches, and deeply nested calculations. The `bugSolution.css` file provides corrected versions and explanations.

## Issues:

* **Flexbox Context:** Using `calc()` within flexbox layouts without properly setting parent element dimensions can lead to unexpected behavior.
* **Unit Mismatches:** Combining different units within a `calc()` expression (e.g., `px` and `%`) without careful consideration can produce incorrect results.
* **Nested Expressions:** Excessive nesting of `calc()` functions reduces code readability and can sometimes impact performance.

## Solutions:

The `bugSolution.css` file showcases how to resolve these issues by providing explicit parent dimensions where necessary, ensuring unit consistency, and flattening nested expressions.