# Express.js Server Not Responding to Requests

This repository demonstrates a common error in Express.js where the server receives requests but fails to respond to them.  This is usually due to a missing `res.send()`, `res.json()`, or similar method in a route handler.

The `bug.js` file shows the problematic code, and `bugSolution.js` provides the corrected version.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js`.
4. Try accessing `http://localhost:3000/` in your browser. You will notice no response from the server.
5. Run `node bugSolution.js` to see the fixed version.