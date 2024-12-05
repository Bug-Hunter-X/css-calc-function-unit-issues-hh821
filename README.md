# CSS `calc()` function unexpected behavior with mixed units

This repository demonstrates an uncommon error that can occur when using the CSS `calc()` function with a mix of percentage and pixel units. The error arises from inconsistencies in browser implementations when interpreting calculations that involve both relative (percentage) and absolute (pixel) units.

The `bug.css` file contains the problematic code, while `bugSolution.css` offers a possible solution and explanation.

The issue stems from the fact that the browser needs to resolve the percentage value before subtracting the pixels. If the parent's width is not explicitly defined in pixels or is dynamically determined, this calculation can be inaccurate.

See the files for details and a potential solution.