# Uncommon HTML/JavaScript Error: Incorrect getElementByid()

This repository demonstrates a subtle error that can occur in JavaScript when interacting with the DOM. The error arises from a typo in the `getElementById` function name, causing a runtime error.

## Bug Description

The `bug.html` file contains a JavaScript snippet that attempts to access an HTML element using `document.getElementByid()`.  There is a typo ('Byid' instead of 'ById').  This will cause the script to throw a runtime error because `getElementByid` is not a valid function.

## Bug Solution

The `bugSolution.html` file shows the corrected code, using the correct function name `document.getElementById()`.  This fixes the error and allows the JavaScript to successfully update the element's content.  Additionally, it includes a check to ensure that the element actually exists before trying to modify it.