# Sudoku Solver AI

Created an AI to solve Sudokus (including Diagonal Sudoku) using constraint propagation and search techniques.

Used constraint propagation to solve the naked twins problem. In the naked twins strategy, we look for two boxes with identical possible values in the same unit (either horizontal, vertical or diagonal). Suppose ['F1':'12', 'I1': '12'], then we can conclude that 1 and 2 must be in F1 and I1 even though we don't know which goes where. So from this assumption, we can eliminate 1 and 2 from all the boxes in the unit corresponding to the twin boxes. So now, if we implement the only choice strategy, it would have much stricter constraints to fill in the possible choices and hence it might lead to a possible solution.


## Note

Can use `pygame` if you want to see the visualization of the solution.
