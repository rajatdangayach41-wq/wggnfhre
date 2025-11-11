Sudoku Validator – README
■ Project Title & Description
Sudoku Validator in C
This project validates a completed 9×9 Sudoku grid using C.
The program stores a Sudoku solution in a 2D array and checks whether it follows all three Sudoku validity rules:
Every row contains numbers 1–9 exactly once
Every column contains numbers 1–9 exactly once
Every 3×3 subgrid contains numbers 1–9 exactly once
The program prints a final verdict: "VALID SOLUTION" or "INVALID SOLUTION".
■ Concepts Used
C Programming Concepts
2D Arrays (9×9 grid)
Nested loops
Functions and return values
If–else decision making
Variable scoping
Hard-coded test data
Standard input/output (printf)
Math/Logic Concepts
Frequency counting
Sudoku rule verification
Grid traversal logic
Subgrid indexing (3×3 matrix jumping)
■ How to Compile
Use the GCC compiler:
gcc sudoku.c -o sudoku      //bash
■ How to Run
After compiling, run the program:
./sudoku      //bash
The output will display either:
VALID SOLUTION
or
INVALID SOLUTION
