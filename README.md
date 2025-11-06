# Arrays, Pointers, and Dynamic Memory (Chapter 9)

A C++ console program designed to demonstrate the relationship between arrays and pointers, pointer arithmetic, and dynamic memory allocation using `new` and `delete[]`.

## Overview
- Builds on previous array examples by introducing pointer traversal and memory management.
- Demonstrates multiple ways of accessing and displaying array elements:
  - Subscript notation (`arr[i]`).
  - Pointer notation (`*(arr + i)`).
  - Pointer dereferencing and incrementing (`*ptr++`).
- Introduces dynamic array allocation with `new` and deallocation with `delete[]`.
- Displays the first elements of dynamically allocated arrays to confirm memory initialization.

## Core Logic
- Declares several fixed arrays and pointers (`pdArray`, `piArray`).
- Uses loops to iterate through arrays and demonstrate:
  - Pointer arithmetic.
  - Access via both subscript and dereferenced pointer forms.
- Allocates dynamic memory for integer arrays, initializes values, and outputs the results.
- Reinforces the concept that the array name (`arr`) acts as a constant pointer to its first element.

## Input Validation
- None required. All data are programmatically generated and displayed for educational demonstration.

## Build & Run
- Visual Studio (Windows): open the solution or create a Console App and add the source file, then **Build → Run**.
- g++ (CLI):
  ```bash
  g++ -std=c++11 -O2 -o ArrayPointerDemo nazarioCPP19.cpp
  ./ArrayPointerDemo
