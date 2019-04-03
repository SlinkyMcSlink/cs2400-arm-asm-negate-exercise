# Preliminaries
1. UAL stands for Unified Assembler Language

# Short Negate
1. What does this program do?
  movs moves the value and sets the negaitive flag, then if the negative flag is set to 1 then it uses 
  RSBMI to reverse subtract and find the absolute value, other otherwise it does nothing.

# Long Negate
1. The short code changes the array in memory, the long code changes the array in the stack
2. Because we did not allocate memory for the array so the compiler does it so the new array was created on the stack.
3. By allocating memory for the array (using Malloc)  and use pointers to adjust values.
