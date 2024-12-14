# CSS Calc() function unexpected behavior with nested percentages

This repository demonstrates an uncommon bug related to the CSS `calc()` function when dealing with nested percentage-based widths.

## Bug Description
The `calc()` function, when used with percentages in nested elements, might produce unexpected results due to the order of operations and how percentages are resolved.

## Reproduction
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected width of the `.element` element.

## Solution
The solution involves avoiding nested percentage-based calculations within the `calc()` function whenever possible.  Consider using fixed pixel values or alternative layout techniques to achieve the desired result.  Refer to `bugSolution.css` for an example fix.