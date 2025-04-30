# SoGA Data Analysis Using C Structs and Sorting Algorithms

## Project Description
This project processes and analyzes life expectancy data from various territories based on health and environmental risk factors using structured C programming. It includes functionality to sort, search, and interpret data from the SoGA dataset.

## Files Included
- `MATA_RANADA.c` – Source code with all logic and function definitions
- `MATA_RANADA.h` – Header file containing struct definitions and macros
- `SoGA_DATASET.txt` – Dataset containing life expectancy data per territory

## Features
- Struct-based storage of SoGA data
- Functions for:
  - Reading and initializing data
  - Sorting by territory name and tobacco-related values
  - Linear and binary search operations
  - Multiple analytical queries (Q1 to Q5)
- Use of struct pointers with both `.` and `->` access
- Cleanly documented code

## Compilation
Use the following command with GCC:
```bash
gcc -Wall MATA_RANADA.c -o MATA_RANADA
```

## Running the Program
Run with I/O redirection in the terminal:
```bash
./MATA_RANADA < SoGA_DATASET.txt > OUTPUT_MATA_RANADA.txt
```

## Authors
- Maria Sarah Althea Mata (S11)
- Arianne Ranada (S11)

## Submission Date
- November 20, 2023
