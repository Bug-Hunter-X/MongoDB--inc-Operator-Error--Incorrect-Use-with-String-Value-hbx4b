# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB to increment numerical fields. The error occurs when attempting to increment a field using a string value rather than a number.

## Bug Report

The provided code snippet incorrectly uses the `$inc` operator with a string ('1') instead of a number (1). This causes a MongoDB error.

## Solution

The solution provided corrects the usage of the `$inc` operator by passing a numeric value for the increment.

## How to reproduce

1. Clone the repository.
2. Set up a MongoDB connection.
3. Run the script `bug.js`.
4. Observe the error.
5. Run the script `bugSolution.js` to see the corrected solution.