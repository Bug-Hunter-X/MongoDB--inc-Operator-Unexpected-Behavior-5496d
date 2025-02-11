# MongoDB $inc Operator Unexpected Behavior

This repository demonstrates an uncommon bug related to the MongoDB `$inc` operator, where incorrect usage leads to unexpected results.

## Bug Description
The original code incorrectly uses the `$inc` operator, resulting in unintended modifications to the field in the document. This is often due to incorrect data types or missing fields in the update query.

## Bug Solution
The solution provides the correct implementation of `$inc` operator with the right syntax and data types.  It highlights proper usage to avoid unintended side-effects.

## How to Reproduce
1.  Set up a MongoDB instance.
2.  Create a collection named `myCollection`.
3.  Insert a document with an `_id` field and a numerical field to be incremented.
4.  Run the incorrect code (found in `bug.js`).
5.  Observe the unexpected behavior and compare it to the expected behavior after running the corrected code (found in `bugSolution.js`).

## Lessons Learned
This example emphasizes the importance of careful attention to detail when using the MongoDB `$inc` operator. Understanding data type handling and the correct syntax is essential for reliable database updates.