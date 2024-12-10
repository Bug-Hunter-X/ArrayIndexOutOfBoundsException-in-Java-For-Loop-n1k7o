# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common error in Java programming: the `ArrayIndexOutOfBoundsException`. This exception occurs when your code tries to access an array element using an index that is either negative or greater than or equal to the array's length.

The `Bug.java` file contains code with this error.  The `BugSolution.java` file provides the corrected code.

## How to Reproduce

1. Clone the repository.
2. Compile `Bug.java` using a Java compiler (like `javac Bug.java`).
3. Run the compiled code (like `java Bug`). You will see an `ArrayIndexOutOfBoundsException`.
4. Now, compile and run `BugSolution.java`. This version will execute without error.

## Lesson Learned

Always be mindful of array indices.  Ensure your loop conditions and array accesses are within the valid range of 0 to array.length - 1.