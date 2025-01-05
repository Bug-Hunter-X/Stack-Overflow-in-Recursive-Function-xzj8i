# Hack Stack Overflow Bug

This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `foo` function calculates the factorial of a number recursively. However, it lacks proper termination condition, leading to infinite recursion for any input greater than 0.  The solution demonstrates how to correctly add a base case to prevent this.

## How to Reproduce

1.  Clone this repository.
2.  Compile and run `bug.hack`.  You should observe a stack overflow error.
3.  Compile and run `bugSolution.hack` to see the corrected version.