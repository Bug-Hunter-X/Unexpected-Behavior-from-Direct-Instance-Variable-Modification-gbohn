# Ruby Bug: Unexpected Behavior from Direct Instance Variable Modification

This repository demonstrates a common yet subtle bug in Ruby related to directly modifying instance variables using `instance_variable_set`.  While sometimes convenient, this approach often bypasses intended class behavior, leading to difficult-to-trace issues.

The `bug.rb` file shows the problem.  The `bugSolution.rb` file presents a more robust and maintainable solution.

**Key takeaway:**  Favor using methods to access and manipulate instance variables, which allows for better control, code clarity, and easier maintenance.