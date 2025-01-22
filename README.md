# CSS `calc()` Issues: Unitless Values and Nesting

This repository demonstrates two less common errors related to using the `calc()` function in CSS: 

1. **Inconsistent Unit Handling:** Using unitless values within `calc()` can lead to inconsistencies across different browsers. 
2. **Nested `calc()` Issues:** While possible, nested `calc()` functions can create complex and hard-to-debug expressions.

The `bug.css` file shows examples of these problems. The `bugSolution.css` file offers improved, more consistent, and easier-to-understand alternatives.