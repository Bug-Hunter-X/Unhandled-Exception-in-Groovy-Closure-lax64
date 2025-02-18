# Unhandled Exception in Groovy Closure

This repository demonstrates a scenario where an exception thrown within a Groovy closure is not handled correctly.

The `bug.groovy` file contains the erroneous code. The exception thrown inside the closure prevents the code after the closure from executing. 

The `bugSolution.groovy` file provides a solution using try-catch blocks to handle the exception gracefully.