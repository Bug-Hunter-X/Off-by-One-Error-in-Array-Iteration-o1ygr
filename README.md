# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= arr.length` should be `i < arr.length`.  The provided solution corrects this issue.

## Bug
The `bug.java` file contains the erroneous code. It leads to an `ArrayIndexOutOfBoundsException` during runtime because the loop tries to access an element outside the array's bounds.

## Solution
The `bugSolution.java` file shows how to fix the error. The loop condition is changed to `i < arr.length`, preventing the out-of-bounds access.