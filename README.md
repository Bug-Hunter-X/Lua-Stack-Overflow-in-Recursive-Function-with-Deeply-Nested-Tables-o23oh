# Lua Stack Overflow in Recursive Function with Deeply Nested Tables

This repository demonstrates a stack overflow error in Lua caused by a recursive function processing deeply nested tables.  The `bug.lua` file contains the erroneous code, and `bugSolution.lua` offers a solution to prevent the stack overflow.

## Description
The Lua interpreter has a limited stack size.  Recursive functions processing very deep data structures can exceed this limit, leading to a stack overflow. The provided example showcases this issue with a recursive function traversing a deeply nested table.

## How to Reproduce
1. Clone this repository.
2. Run `bug.lua` using a Lua interpreter.
3. Observe the stack overflow error.

## Solution
The `bugSolution.lua` file presents a solution using an iterative approach instead of recursion to prevent the stack overflow error. This iterative approach avoids the unbounded stack growth of the recursive function.

## Contributing
Feel free to contribute to this example by adding more examples or improving the code quality.