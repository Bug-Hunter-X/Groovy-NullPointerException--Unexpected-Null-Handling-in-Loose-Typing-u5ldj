# Groovy NullPointerException: Unexpected Null Handling

This repository demonstrates a common issue in Groovy related to null pointer exceptions arising from loose typing.  Groovy's flexible nature can mask potential errors when dealing with null values unless explicitly addressed.

The `bug.groovy` file contains a function that adds two numbers but doesn't properly handle null inputs. The solution demonstrates safe null handling in `bugSolution.groovy`.

## Reproducing the Bug

1. Clone this repository.
2. Run `groovy bug.groovy`
3. Observe the unexpected null outputs and potential for exceptions in more complex scenarios.

## Solution

The `bugSolution.groovy` file presents a more robust approach using Groovy's safe navigation operator (`?.`) and elvis operator (`?:`) for safe null handling.