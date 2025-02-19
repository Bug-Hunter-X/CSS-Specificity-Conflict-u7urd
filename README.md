# CSS Specificity Conflict Bug
This repository demonstrates a common CSS issue: specificity conflicts. The `bug.css` file contains CSS that leads to an unexpected background color due to selector specificity.  The `bugSolution.css` file provides a solution to this problem.

## Bug Description
The goal is to have the inner div have a blue background.  However, due to the specificity of the selector affecting the outer div, the inner div inherits the red background unexpectedly.  The solution shows how to correctly style both divs without unintended conflicts.