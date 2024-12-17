# PHP: Unexpected Array Summation with String-like Numbers
This example demonstrates an uncommon error in PHP when dealing with array summation. If an array contains a string that resembles a number (e.g., '4a'), the `+` operator will perform string concatenation instead of numeric addition, leading to an unexpected result.  This bug highlights the importance of type checking when working with arrays and numbers in PHP.

## Steps to Reproduce
1. Run the provided `bug.php` script.
2. Observe the unexpected output.

## Solution
The solution involves type checking or using a function to handle potential type mismatches before performing the summation. See `bugSolution.php` for a corrected version.