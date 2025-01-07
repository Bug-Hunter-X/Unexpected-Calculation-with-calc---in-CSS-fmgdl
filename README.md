# Unexpected Calculation with calc() in CSS

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with percentages and other units.  The issue occurs when the parent element's width is not explicitly defined, or when the parent width is itself calculated. The resulting calculation may be inconsistent or incorrect.

The `bug.css` file shows the problematic CSS.  The `bugSolution.css` demonstrates a solution.

## Solution
Ensuring the parent element has a defined width, or using a different approach that avoids mixed unit calculations, is crucial for predictable results.