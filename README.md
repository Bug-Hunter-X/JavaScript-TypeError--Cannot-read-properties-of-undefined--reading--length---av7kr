# JavaScript Undefined Property Access Bug

This repository demonstrates a common error in JavaScript: attempting to access a property of an undefined value. The `foo` function in `bug.js` correctly handles `null` input, but throws a `TypeError` when passed an `undefined` value.  This highlights the importance of robust null and undefined checks in JavaScript.

## How to reproduce

1. Clone this repository.
2. Run `node bug.js`.
3. Observe the `TypeError` when the function is called with an undefined argument.

## Solution

The `bugSolution.js` file provides a corrected version of the function, using explicit null and undefined checks to prevent the error.