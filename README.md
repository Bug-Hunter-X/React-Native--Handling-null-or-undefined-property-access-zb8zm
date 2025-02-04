# React Native: Handling Null or Undefined Property Access

This repository demonstrates a common error in React Native applications: attempting to access properties of an object that is `null` or `undefined`. This typically happens when dealing with asynchronous operations, where data may not be available immediately. The error message usually looks like this: `Cannot read properties of undefined (reading 'someProperty')`.

The `bug.js` file shows an example of code that causes this error. The `bugSolution.js` file provides a solution using optional chaining and nullish coalescing.