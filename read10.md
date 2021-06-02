# Debugging
## Order of execution
### It is vital to understand how the code is executed in order to be able to find errors in the code

## Execution context
### There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope.
## EXECUTION CONTEXT 
### Every statement in a script lives in one of three execution contexts: 
### GLOBAL CONTEXT: Code that is in the script, but not in a function.There is only one global context in any page. 
### FUNCTION CONTEXT: Code that is being run within a function. Each function has its own function context. 
### EVAL CONTEXT (NOT SHOWN): Text is executed like code in an internal functioncalled eva l {)

## VARIABLE SCOPE 

### GLOBAL SCOPE: If a variable is declared outside a function, it can be used anywhere because it has global scope.If you do not use the var keyword when creating a variable, it is placed in global scope. 
### FUNCTION-LEVEL SCOPE: When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope. 

## Error Objects:
### There are seven types of built-in error objects in JavaScript

### Generic error - the other errors are all based upon this error Syntax has not been followed Ref erenceError Tried to eference a variable that is not declared/within scope 
### TypeError 
### Range Error 
### URI Error 
### EvalEr error: An unexpected data type that cannot be coerced Numbers not in acceptable range encode
### URI ().decodeURI(),and similar methods used incorrectly 

