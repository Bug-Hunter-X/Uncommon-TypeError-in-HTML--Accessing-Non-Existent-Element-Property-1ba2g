# Uncommon HTML Bug: Accessing Non-Existent Element Property

This repository demonstrates an uncommon error in HTML: attempting to access a property that does not exist on a DOM element. This can lead to a `TypeError` and unexpected behavior.

The `bug.html` file contains the buggy code. The `bugSolution.html` provides a corrected version.

The error stems from accessing the `nonExistentProperty` on the `myDiv` element, which doesn't exist.

The solution involves careful checking for the existence of properties before attempting to access them.