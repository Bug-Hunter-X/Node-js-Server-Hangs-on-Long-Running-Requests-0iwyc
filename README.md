# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js where a server can hang due to long-running operations blocking the event loop.  The `server.js` file contains code that simulates a 5-second delay, causing the server to become unresponsive during that time.  This is problematic because Node.js is single-threaded, and long operations can prevent it from handling other requests.

`serverSolution.js` provides a solution using asynchronous operations or worker threads to prevent this blocking behavior.