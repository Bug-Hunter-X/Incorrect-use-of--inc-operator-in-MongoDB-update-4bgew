# Incorrect use of $inc operator in MongoDB update
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numerical field by a specified amount.  However, providing a non-numeric value will result in unexpected behaviour or a query failure.

The `bug.js` file showcases the incorrect usage, while `bugSolution.js` presents the corrected version.  This example is useful for understanding and avoiding this specific MongoDB error.