# Ada Array Indexing and Exception Handling

This repository contains an example of a potential error in Ada code related to array indexing and exception handling. The code iterates through an array and modifies its elements. However, it does not include explicit error handling for potential out-of-bounds access exceptions.  This can lead to runtime crashes if the array's size changes unexpectedly during the loop.

The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides a corrected version with improved exception handling.