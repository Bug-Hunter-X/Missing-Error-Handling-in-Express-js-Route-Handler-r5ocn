# Express.js Route Handler Error Handling Bug

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The `bug.js` file contains a route that fetches a user by ID.  It fails to handle cases where the ID is not a valid integer, potentially leading to unexpected behavior or application crashes.

The `bugSolution.js` file provides a corrected version with proper error handling, demonstrating how to prevent this issue.