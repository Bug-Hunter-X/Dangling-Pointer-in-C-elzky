# Dangling Pointer Bug in C

This repository demonstrates a common error in C programming: dangling pointers.  A dangling pointer occurs when a pointer variable points to memory that has been freed or is no longer valid.  Accessing memory through a dangling pointer leads to undefined behavior, which can result in crashes or unpredictable results.

The `bug.c` file contains code that exhibits this issue. The solution is shown in `bugSolution.c`.