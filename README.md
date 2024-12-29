# TypeScript Runtime Error from Missing Object Properties

This example demonstrates a common issue in TypeScript where the type system doesn't always prevent runtime errors. Specifically, if an object is missing a property that's accessed, a runtime error will occur.

The `bug.ts` file contains the problematic code, and `bugSolution.ts` provides a solution using optional properties and type guards.