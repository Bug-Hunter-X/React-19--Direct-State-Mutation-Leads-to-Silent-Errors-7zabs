# React 19: Silent State Mutation Bug

This repository demonstrates a subtle bug in React 19 related to directly mutating state variables.  Directly modifying state variables (using assignment operators like `=`) instead of using the setter function provided by `useState` will silently fail to update the component. This can lead to difficult-to-debug issues, especially in larger applications.

The `bug.js` file contains the erroneous code.  The correct solution is shown in `bugSolution.js`.