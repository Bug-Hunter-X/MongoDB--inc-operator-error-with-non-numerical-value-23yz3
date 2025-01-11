# MongoDB $inc Operator Error
This example demonstrates an error that occurs when using MongoDB's `$inc` operator with a non-numerical value.  The `$inc` operator is designed to increment a numerical field by a specified amount. Attempting to increment with a string value will result in an error.

## Bug
The bug lies in using 'abc' (a string) as the increment value with the $inc operator. This leads to an error as the operator expects a number.

## Solution
The correct way is to provide a valid number to the `$inc` operator.