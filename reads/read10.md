# ORDER OF EXECUTION:

**To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run**:

# EXECUT.ION CONTEXTS:

> The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new 
new execution context. They correspond to variable scope.


> #### EXECUTION CONTEXT:
>
> - GLOBAL CONTEXT.
> - FUNCTION CONTEXT.
>
>  EVAL CONTEXT (NOT SHOWN) 
___

### EXECUTION CONTEXT & HOISTING:
1: PREPARE 
* The new scope is created. 
* Variables, functions, and arguments are created .
*  The value of the this keyword is determined.

2: EXECUTE
*  Now it can assign values to variables.
*  Reference functions and run their code.
* Execute statements.

### UNDERSTANDING ERRORS:

> If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code. 

![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors.jpg)

### HOW TO DEAL WITH ERRORS:

* DEBUG THE SCRIPT TO FIX ERRORS:
> If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.

* HANDLE ERRORS GRACEFULLY:
> You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements.
___

![](https://www.tutsmake.com/wp-content/uploads/2020/05/Types-of-Errors-In-JavaScript.jpeg)
___

# A DEBUGGING WORKFLOW:

**Debugging is about deduction: eliminating potential causes of an error. 
Here is a workflow for techniques you will meet over the next 20 pages. 
Try to narrow down where the problem might be, then look for clues.** 

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing-1200x675.png)

### WHERE IS THE PROBLEM?
1-Look at the error message, it tells you: 
* The relevant script that caused the problem. 
* The line number where it became a problem for 
the interpreter. (As you will see, the cause of 
the error may be earlier in a script; but this is the 
point at which the script could not continue.) 
* The type of error (although the underlying cause 
of the error may be different).

2. Check how far the script is running. 
Use tools to write messages to the console to tell 
how far your script has executed.

3. Use breakpoints where things are going wrong. 
They let you pause execution and inspect the values 
that are stored in variables.

> The JavaScript console is just one of several developer tools that are 
found in all modern browsers.