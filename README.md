# Unexpected Return Value from Assignment Expressions in Ruby

This repository demonstrates an uncommon yet potentially problematic behavior in Ruby: assignment expressions return the assigned value, not `nil`. This can lead to unexpected results, particularly within conditional statements or when a `nil` return value is anticipated.

The `bug.rb` file showcases the issue. The `bugSolution.rb` file demonstrates a solution to make the return value consistent for better code clarity and predictability.

## How to reproduce

1. Clone this repository
2. Run `ruby bug.rb`
3. Observe the unexpected output from the assignment expression within the `puts` statement.