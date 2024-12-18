# Unexpected Behavior of :nth-child(n) with Pseudo-elements in CSS

This repository demonstrates a common yet subtle bug in CSS involving the `:nth-child(n)` selector when used in conjunction with pseudo-elements like `::before` or `::after`.

The issue arises because the `:nth-child(n)` selector targets elements based on their position among their siblings.  When paired with a pseudo-element, the intended styling may not apply correctly, leading to unexpected visual inconsistencies.

The `bug.css` file shows the problematic code, and `bugSolution.css` provides a solution by applying the styling directly to the element using a different selector or using a more specific selector to target each element individually.

This can be a tricky bug to debug, as the unexpected behavior isn't always immediately apparent.