# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates a subtle bug related to CSS specificity and declaration order.  A seemingly correct selector fails to apply the expected styles due to a less obvious specificity conflict and the unexpected influence of declaration order.

## The Problem

The `bug.css` file contains CSS that exhibits this unexpected behavior. A more specific selector is incorrectly overridden by a selector with the same specificity that is declared later in the stylesheet.

## The Solution

The `bugSolution.css` file provides a corrected version of the CSS.  The solution involves carefully managing specificity and ensuring that the intended styles are applied based on their correct precedence.