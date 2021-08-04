# Build Websites JAVASCRIPT & JQUERY
## Ch. 10, Error Handling & Debugging
* UNDERSTANDING
SCOPE
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 
* UNDERSTANDING ERRORS 
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 
* ERROR OBJECTS 
Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 
* HOW TO DEAL WITH
ERRORS
Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors. 
* A DEBUGGING
WORKFLOW
Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues. 
* BROWSER DEV TOOLS &
JAVASCRIPT CONSOLE 
The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be. 
* HOW TO LOOK AT ERRORS
IN CHROME 
The console will show you when there is an
error in your JavaScript. It also displays the line
where it became a problem for the interpreter. 
* BREAKPOINTS  
You can pause the execution of a script on any
line using breakpoints. Then you can check the
values stored in variables at that point in time. 
* STEPPING THROUGH CODE 
If you set multiple breakpoints, you can step
through them one-by-one to see where values
change and a problem might occur. 
* CONDITIONAL
BREAKPOINTS
You can indicate that a breakpoint should be
triggered only if a condition that you specify is
met. The condition can use existing variables. 
### summary
* If you understand execution contexts (which have two
stages) and stacks, you are more likely to find the error
in your code. 
* Debugging is the process of finding errors. It involves a
process of deduction. 
* The console helps narrow down the area in which the
error is located, so you can try to find the exact error. 
* JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error. 
* If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 