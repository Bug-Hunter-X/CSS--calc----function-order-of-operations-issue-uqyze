# CSS `calc()` Function Order of Operations Issue

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The bug arises when combining percentages and lengths within the `calc()` function, leading to inconsistent results across different browsers due to variations in how the order of operations is handled.

## Bug Description
The `calc()` function in CSS allows for dynamic calculations. However, when combining percentages and lengths (e.g., `50% - 10px`), the order of operations can be interpreted differently by various browsers. This inconsistency results in unexpected layout issues.

## Reproduction
The `bug.css` file contains the problematic CSS code.  Observe the differences in rendering across various browsers.

## Solution
The `bugSolution.css` file presents a solution that addresses the issue and ensures consistent behavior across browsers. This solution involves rearranging the calculation or using alternative techniques (explained in more detail in the solution file).