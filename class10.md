#  Error handling and debugging 

_Javascript is deffecult to learn and anyone made mistake when writing it and the debugging is :_
1. **The console & div tools**
+ Tools built into the browser that help you hunt for errors.
2. **handling and debugging**
+ COMMON PROBLEMS Common sources of errors, and how to solve them.
3. **handling errors** 
+ How code can deal with potential errors gra cefully

### execution context 
1. Globle functions 
+ Code that is in the script, but not in a function.There is only on global context in any page.
2. Eval function
+ Text is executed like code in an internal function
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
called eva l {)
3. GLOBAL SCOPE
 + If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.

### UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.