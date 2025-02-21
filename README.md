# Elixir Enum.each and throw unexpected behavior

This repository demonstrates a subtle issue with using `Enum.each` and `throw` in Elixir.  While `throw` is intended to halt execution, it might not behave as expected with `Enum.each` unless properly handled.

The `bug.exs` file shows the problem.  `bugSolution.exs` provides a solution.