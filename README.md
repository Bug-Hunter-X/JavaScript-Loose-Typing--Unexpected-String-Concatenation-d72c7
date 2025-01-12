# JavaScript Loose Typing Bug

This repository demonstrates a common error in JavaScript stemming from its loose typing system.  The `foo` function is intended to add two numbers, but due to the implicit type coercion, it performs string concatenation when given a number and a string.

## Bug
The `bug.js` file contains the buggy code.  Running it will show that passing a number and a string to the `foo` function results in unexpected string concatenation rather than numerical addition.

## Solution
The `bugSolution.js` file provides a solution using explicit type checking to ensure that both inputs are numbers before performing the addition.  This prevents the unexpected string concatenation.

This example highlights the importance of explicit type checking and careful handling of data types in JavaScript to avoid such subtle bugs.