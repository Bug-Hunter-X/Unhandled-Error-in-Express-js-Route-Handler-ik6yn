# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.

The `bug.js` file shows a route that fetches a user by ID. If the ID is not a number, or if a user with that ID is not found, it throws an error. 

The `bugSolution.js` file shows a corrected version with proper error handling.