# MongoDB $inc Operator with String Field

This repository demonstrates an incorrect usage of the MongoDB `$inc` operator. The `$inc` operator is designed to increment numeric values. Using it on a string field will result in an error.

## Bug
The `bug.js` file contains code that attempts to increment a string field using `$inc`. This will throw a `TypeError` because the `$inc` operator expects a numeric value.

## Solution
The `bugSolution.js` file demonstrates the correct way to handle such a situation, showing ways to avoid the error and ensuring the data integrity in the MongoDB database.