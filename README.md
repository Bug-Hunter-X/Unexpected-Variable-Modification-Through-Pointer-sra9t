# Unexpected Variable Modification Through Pointer

This repository demonstrates a common yet easily overlooked bug in C programming involving pointer arithmetic and variable modification.  The code modifies a variable's value indirectly via a pointer, highlighting the importance of understanding pointer behavior for avoiding unexpected results.

## Bug Description

The `bug.c` file contains a simple C program that initializes an integer variable and then modifies its value using a pointer. While seemingly straightforward, the subtle issue lies in the potential for unexpected behavior if not carefully managed. 

The `bugSolution.c` file provides a corrected version that addresses these potential issues.

## How to Run

1.  Clone this repository.
2.  Compile the C file using a C compiler (like GCC): 
   ```bash
   gcc bug.c -o bug
   gcc bugSolution.c -o bugSolution
   ```
3.  Run the executable:
   ```bash
   ./bug
   ./bugSolution
   ```

Observe the output to understand the bug and its solution.  The solution file illustrates safer handling of memory pointers.
