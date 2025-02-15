# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value to `$inc` instead of a number, which results in an incorrect update or an error.

## Bug
The provided `bug.js` file contains an example of this error. Attempting to increment a field by a string value will not perform the numerical increment, leading to unexpected results. 

## Solution
The `bugSolution.js` file corrects the error by using a numeric value with the `$inc` operator.