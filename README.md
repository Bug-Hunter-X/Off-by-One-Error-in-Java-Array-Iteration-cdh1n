# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

The bug arises from incorrectly using the `<=` operator in the for loop condition, leading to an attempt to access an index that is out of bounds.  This is a subtle but frequently occurring error, especially when dealing with array indices. The fix simply changes `<=` to `<`, ensuring that the loop iterates only within the valid index range of the array.

This example highlights the importance of careful attention to array indexing to prevent runtime exceptions.