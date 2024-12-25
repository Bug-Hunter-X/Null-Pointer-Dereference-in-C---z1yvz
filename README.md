# Null Pointer Dereference Bug in C++

This repository demonstrates a common C++ bug: dereferencing a null pointer.  The `bug.cpp` file contains the problematic code.  The `bugSolution.cpp` file shows how to correct the issue by checking for null before dereferencing.

**Problem:**
Attempting to access memory through a null pointer leads to unpredictable behavior, typically causing a program crash.  This is a critical error that must be avoided.

**Solution:**
Always check if a pointer is null before dereferencing it.  This prevents the program from accessing invalid memory addresses.

This example highlights the importance of careful pointer handling in C++.