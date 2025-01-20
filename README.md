# Unreachable Code in Julia

This repository demonstrates an example of unreachable code in a Julia function. The function `myfunction` includes a `return` statement within both branches of the `if-else` block, making the final `return 0` statement unreachable. This can lead to unexpected behavior or confusion when reading the code.

## Bug

The `bug.jl` file contains the function with the unreachable code.

## Solution

The `bugSolution.jl` file shows the corrected version of the function, removing the unreachable statement.

This example illustrates the importance of careful code structuring in Julia to avoid unnecessary and potentially problematic code.