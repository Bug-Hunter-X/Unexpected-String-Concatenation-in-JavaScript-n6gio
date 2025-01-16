# Unexpected String Concatenation in JavaScript
This example demonstrates a common error in JavaScript related to loose typing. When performing addition with a number and a string, JavaScript will implicitly convert the number to a string and perform string concatenation instead of numerical addition.  This can lead to unexpected results and subtle bugs in your code.

## How to Reproduce
1. Run `bug.js`.
2. Observe that the output is "12" instead of 3, demonstrating the unintended string concatenation.

## Solution
The `bugSolution.js` file provides a solution by explicitly converting the string to a number using `parseInt()` before performing the addition.
