# 15puzzleSolver

in the "eval_pos" function, please note that in order to keep the heuristic admissible you should use "for num in range(1,15+1)" instead of "for num in [None]+range(1,15+1)". 
otherwise you won't get an optimal solution.
