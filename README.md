# Unhandled Arithmetic Operator Bug in JavaScript Calculator

This repository demonstrates a common bug in JavaScript: failing to handle all possible cases in a switch statement.  The `operate` function in `bug.js` performs basic arithmetic operations (+, -, *, /). However, it lacks handling for the modulus operator (`%`), resulting in an error when attempting to use it.

The solution, provided in `bugSolution.js`, addresses this by adding a case for the modulus operator within the switch statement, making the function more robust and less prone to errors.

## How to reproduce

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js`.
3. Run `bug.js`. Observe that it throws an error when attempting a modulus operation.
4. Run `bugSolution.js`. Observe the correct functionality including modulus operations.

This example highlights the importance of comprehensive error handling and thorough testing in your JavaScript code.