# Julia Zero Handling Bug

This repository demonstrates a subtle issue in Julia related to how zero is handled within conditional expressions. The `myfunction` function appears to work correctly for positive and negative numbers, but exhibits unexpected behavior when the input is zero. 

The solution provides a way to explicitly handle the case of zero, preventing unexpected results. 

## Steps to Reproduce

1. Clone this repository.
2. Run `bug.jl` to see the unexpected behavior.
3. Run `bugSolution.jl` to see the corrected behavior.