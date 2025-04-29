1: Line 9 prints out "values added: 20"
2: Line 13 prints out " final result: 20"
3: You should not use `var` because using `var` lets the variable ignore code blocks
and thus allows for a global variable to be declared instead of the intended local variable usage.
`var` demonstrates its ability to pierce through code blocks as demonstrated by the code.
4: Line 9 prints out "values added: 20"
5: Line 13 should print out an error stating that `result` is not defined because since `result` was defined in the previous code block using the `let` declaration, it is out of the scope and will cause
an error.
6: Line 9 would print out an error because since result is declared as a `const` its value cannot be
resassigned. 
7: Line 13 should print out an error stating that `result` is not defined because since `result` was defined in the previous code block using the `let` declaration, it is out of the scope and will cause
an error.