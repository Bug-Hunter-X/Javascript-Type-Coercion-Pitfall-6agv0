# Javascript Type Coercion Pitfall

This example demonstrates a common Javascript pitfall involving type coercion with the + operator.  When adding a number and a string, Javascript will implicitly convert the number to a string and perform string concatenation instead of numerical addition. This behavior can lead to unexpected results if not carefully considered.

## Bug
The `bug.js` file shows how the + operator behaves differently depending on whether both operands are numbers or whether one is a string.

## Solution
The `bugSolution.js` file presents a solution that uses explicit type conversion to ensure that both operands are numbers before performing addition.  This approach prevents unexpected string concatenation and promotes more robust code.