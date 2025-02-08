# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element outside its bounds. The `bugSolution.java` file provides the corrected code.
## Bug Description
The bug arises from an off-by-one error in the loop condition. The loop iterates from 0 up to and including `arr.length`, attempting to access `arr[5]` which is beyond the valid index range (0-4). This results in an `ArrayIndexOutOfBoundsException`.
## Solution
The solution modifies the loop condition to `i < arr.length`, ensuring that the loop only iterates within the valid index range of the array.