# Type 'string' is not assignable to type 'number' in TypeScript

This repository demonstrates a common TypeScript error: 'Type 'string' is not assignable to type 'number'. This error occurs when a function or variable expecting a number receives a string value.  This is a key example of TypeScript's type safety; preventing runtime errors by catching them during compilation.

## How to Reproduce

1. Clone the repository.
2. Open `bug.ts`.
3. Run the TypeScript compiler (tsc) to observe the error.

## Solution

The solution involves ensuring that only numbers are passed to the function. String values must be converted to numbers before passing them to the function or performing numerical operations.  See `bugSolution.ts` for an example using `parseInt`.