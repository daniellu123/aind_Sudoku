# Artificial Intelligence Nanodegree
## Introductory Project: Diagonal Sudoku Solver
This project includes two tasks. The first one is sovlering naked twin sudoku with constrained propogation method, and the second is diagnoal sudoku, which among the two main diagonals, the numbers 1 to 9 should all appear exactly once.

# 1. naked twins
The naked twins technique is the following. Consider the following puzzle, and look at the two highlighted boxes, 'F3' and 'I3'.


Question
Q: How do we use constraint propagation to solve the naked twins problem?  
A: We search the squares whoes length equals 2 and with same digits in one unit. And then eliminate the two digits from other squares in the same unit. By applying this operation to all of naked twin, that is constraint propogation, we can reach the goal of solution.

# 2. Diagnoal sudoku
A diagonal sudoku is like a regular sudoku, except that among the two main diagonals, the numbers 1 to 9 should all appear exactly once.

Question
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: Comparing with general sudoku problem, we can sovlering diagnoal sudoku by adding the two main dignals to the unit list. 

# 3. Run the program
For running general sudoku, please run solution.py.

For verifying naked twins and diagnoal sudoku, please run solution_test.py
