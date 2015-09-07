# oclint_argument_list_too_long_solution
Solution to oclint error "Argument list too long"

When we have too many codes in our project, the compile_commands.json could be pretty large.
And when we use oclint to analyze the json file, we will get an error "Argument list too long".
Obviously, there are too many lines in the json file. And I give a solution to the problem.
```
python oclint.py compile_commands.json
```
