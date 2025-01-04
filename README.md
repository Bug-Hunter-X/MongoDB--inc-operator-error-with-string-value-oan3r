# MongoDB $inc Operator Error with String Value
This repository demonstrates a common error encountered when using the `$inc` operator in MongoDB update operations.  The error occurs when a string value is passed instead of a numeric value.

## Bug Description
The provided code attempts to increment the 'field' value in a document where the _id is 1. The error is caused by using the string "1" instead of the number 1 with the `$inc` operator. The `$inc` operator only accepts numerical values for incrementing.