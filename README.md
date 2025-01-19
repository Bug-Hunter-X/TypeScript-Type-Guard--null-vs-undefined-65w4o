# TypeScript Type Guard: Handling null and undefined

This repository demonstrates a common issue in TypeScript type guards: the distinction between `null` and `undefined`. While type guards effectively check for `null`, they often don't explicitly account for `undefined`, leading to runtime errors.

The `bug.ts` file shows a function that handles `null` correctly but throws an error when `undefined` is passed.  `bugSolution.ts` offers a solution to make the type guard more robust.