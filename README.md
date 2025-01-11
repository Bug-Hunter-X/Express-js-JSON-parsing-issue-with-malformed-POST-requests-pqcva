# Express.js JSON Parsing Issue

This repository demonstrates a common issue encountered when using Express.js to handle JSON data in POST requests.  If a request body is malformed or doesn't adhere to the JSON standard, the `express.json()` middleware might not parse it correctly. This can result in `req.body` being undefined or empty, leading to unexpected behavior and errors.

The `bug.js` file contains the problematic code, showcasing how a malformed JSON request can lead to errors. The solution is provided in `bugSolution.js`.