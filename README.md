# Lua Nil Handling Bug

This repository demonstrates a common error in Lua related to handling `nil` values in function arguments. The `foo` function demonstrates how checks for `nil` values, and their order, are critical to avoid unexpected output.

The `bug.lua` file contains the erroneous code, producing unexpected output for certain inputs. The corrected version is provided in `bugSolution.lua`, highlighting the importance of explicitly handling `nil` in each branch of conditional logic.