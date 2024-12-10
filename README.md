# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a subtle but potentially problematic error in HTML/JavaScript: attempting to access and modify the properties of an HTML element that does not exist in the DOM. 

The `bug.html` file contains the erroneous code.  The `bugSolution.html` file shows how to fix this by checking for the element's existence before attempting to manipulate it. 

This type of error can be challenging to debug because it often doesn't produce a visible error message in the browser, leading to unexpected behavior or silent failures.