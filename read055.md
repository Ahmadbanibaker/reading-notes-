# Expressions and operators
## Operators
- ## Assignment operators
### An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

- ## Comparison operators
### A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

- ## Arithmetic operators
###  An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).

- ## Logical operators
### Examples of expressions that can be converted to false are those that evaluate to null, 0, NaN, the empty string (""), or undefined.

- ## Expressions
### An expression is any valid unit of code that resolves to a value.

### Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.

### The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven.


<<<<<<< HEAD
- ## while statement
### A while statement executes its statements as long as a specified condition evaluates to true.If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

### The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

- ## for statement
### A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
### The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)


![for vs while loop](https://i.pinimg.com/originals/c2/56/8f/c2568f7e6bc7af034e5f1c42d3747e64.png)



