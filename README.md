# F# Mutable Variable Bug

This repository demonstrates a common pitfall when working with mutable variables and functions in F#. The `bug.fs` file contains code that exhibits unexpected behavior due to the way mutable variables are handled in F#.

The solution, provided in `bugSolution.fs`, addresses the issue by correctly updating the mutable variable `z` to reflect changes in `x` and `y`.