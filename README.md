# Unexpected Output in setTimeout Loop with Closure

This repository demonstrates a common JavaScript error related to closures and the `setTimeout` function within a loop.

The `bug.js` file contains a function that uses a `for` loop and `setTimeout` to log numbers from 0 to 9. However, due to how closures work in JavaScript, the output is not what you might initially expect.

The `bugSolution.js` file provides a corrected version of the code, explaining how to avoid this closure issue.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` in your browser's developer console, or use node.js to run it.
3. Observe that the output shows '10' ten times instead of 0 to 9.
4. Open `bugSolution.js`,  it fixes the bug and logs the expected result.