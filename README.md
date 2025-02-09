# PHP Ternary Operator Gotchas

This repository demonstrates subtle issues that can arise when using PHP's ternary operator, specifically concerning operator precedence and handling of functions that might return falsy values.  The `bug.php` file shows examples of incorrect usage, while `bugSolution.php` presents the corrected code.

The core problem lies in the sometimes-unintuitive order of operations and how PHP handles null and other values that evaluate to false in boolean contexts.

**Key Issues Addressed:**

* Incorrect operator precedence when using the ternary operator in more complex expressions within array assignments.
* Unnecessary or duplicate function calls when the ternary operator's condition and value rely on the same function, potentially causing side effects or performance issues. 

This repository aims to highlight these common errors and provide clear solutions to prevent such issues in your PHP code.