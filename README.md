# React useEffect setInterval Memory Leak

This repository demonstrates a common error in React: using `setInterval` within a `useEffect` hook without proper cleanup. This leads to a memory leak, as the interval continues to run even after the component is unmounted.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the correct implementation.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the behavior in the browser.