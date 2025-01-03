# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java error: `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains code that produces this exception.  The solution, demonstrating proper array access, is in `BugSolution.java`.

The error arises when trying to access an array element using an index that's either negative or greater than or equal to the array's length.  Always ensure your array indices are within the bounds [0, array.length - 1].