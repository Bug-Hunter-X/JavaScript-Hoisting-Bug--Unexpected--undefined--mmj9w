# JavaScript Hoisting Bug

This repository demonstrates a common JavaScript bug related to hoisting.  The code in `bug.js` attempts to log the value of a variable before it's declared and assigned. This results in 'undefined' being printed to the console because of JavaScript's hoisting mechanism. The solution provided in `bugSolution.js` showcases how to correct this issue by ensuring the variable is declared and assigned before use.