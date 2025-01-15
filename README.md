This repository demonstrates a common yet subtle issue in CSS when using the `calc()` function to calculate widths.  The problem arises when the parent element of the target element has padding or a border. The `calc()` function bases its calculation on the content area of the element, excluding padding and border. This can lead to unexpected results if these properties are not accounted for.

The `bug.css` file shows the problematic code, and `bugSolution.css` offers a solution using the `box-sizing` property.