# MongoDB $inc Operator Error with String Increment Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value.  However, passing a string value to `$inc` will lead to an unexpected result, and will not increment the value properly.

The `bug.js` file contains the incorrect implementation and `bugSolution.js` provides the correct solution.

## Bug

The bug lies in the incorrect usage of the `$inc` operator, using a string value instead of a number. This will result in a failure to increment the `count` field in the document.