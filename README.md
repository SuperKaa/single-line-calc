# single-line-calc
a calculator made in python on only one line of code, using eval()

## How it works
it uses the eval() function built into python which evaluates a string input for any executable python code, and + - * / all work in python so it prints the answer.

## Negatives
it uses the eval() function which will allow the execution of any python code including eval("__import__("os").system("echo hacked!")") and replacing "echo hacked!" with any system command will allow it to run.
