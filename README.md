# Python Average Calculation with Empty List Handling

This repository demonstrates a Python function for calculating the average of a list of numbers and addresses the potential `ZeroDivisionError` when dealing with empty lists.  The solution includes improved error handling for a more robust function.

## Bug
The original `calculate_average` function handles empty lists by returning 0, preventing a division by zero error.  However, this could be improved by explicitly checking for non-numeric inputs or providing a more informative error message.