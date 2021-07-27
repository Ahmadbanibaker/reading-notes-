# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 3: Lists 
* Ordered Lists : The ordered list is created with 
the < ol> element.Each item in the list is placed 
between an opening < li> tag 
and a closing < /li> tag. (The li
stands for list item.)
* Unordered Lists : The unordered list is created 
with the < ul> element.Each item in the list is placed 
between an opening < li> tag 
and a closing < /li> tag. (The li
stands for list item.)
* Definition Lists : The definition list is created with 
the < dl> element and usually 
consists of a series of terms and 
their definitions.Inside the < dl> element you will 
usually see pairs of < dt> and 
< dd> elements. This is used to contain the term 
being defined (the definition 
term).This is used to contain the 
definition.
* Nested Lists : You can put a second list inside 
an < li> element to create a sublist or nested list.
## Summary 
* There are three types of HTML lists: ordered, 
unordered, and definition. 
* Ordered lists use numbers.
* Unordered lists use bullets.
* Definition lists are used to define terminology.
* Lists can be nested inside one another

## Chapter 13: Boxes 
* Box Dimensions : width, height By default a box is sized just big 
enough to hold its contents. To 
set your own dimensions for a 
box you can use the height and 
width properties.The most popular ways to 
specify the size of a box are 
to use pixels, percentages, or 
ems. Traditionally, pixels have 
been the most popular method 
because they allow designers to 
accurately control their size.
* Limiting width : (min-width, max-width
) Some page designs expand and 
shrink to fit the size of the user's 
screen. In such designs, the 
min-width property specifies 
the smallest size a box can be 
displayed at when the browser 
window is narrow, and the 
max-width property indicates 
the maximum width a box can 
stretch to when the browser 
window is wide.
* Limiting height : (min-height, max-height) In the same way that you might 
want to limit the width of a box 
on a page, you may also want 
to limit the height of it. This is 
achieved using the min-height
and max-height properties.
* Overflowing Content : The overflow property tells the 
browser what to do if the content 
contained within a box is larger 
than the box itself. It can have 
one of two values:hidden
This property simply hides any 
extra content that does not fit in 
the box.scroll
This property adds a scrollbar to 
the box so that users can scroll 
to see the missing content.
* border-width : The border-width property 
is used to control the width 
of a border. The value of this 
property can either be given 
in pixels or using one of the 
following values:
thin
medium
thick
(You cannot use percentages 
with this property.).
* border-style : You can control the style of a 
border using the border-style
property. This property can take 
the following values:
solid a single solid line
dotted a series of square dots
(if your border is 2px wide, then 
the dots are 2px squared with a 
2px gap between each dot)
dashed a series of short lines.double two solid lines (the 
value of the border-width
property creates the sum of the 
two lines)
groove appears to be carved 
into the page
ridge appears to stick out from 
the page
inset appears embedded into 
the page
outset looks like it is coming 
out of the screen
hidden / none no border is 
shown
You can individually change the 
styles of different borders using:
border-top-style
border-left-style
border-right-style
border-bottom-style.
* border-color : You can specify the color of a 
border using either RGB values, 
hex codes or CSS color names It is possible to individually 
control the colors of the borders 
on different sides of a box using:
border-top-color
border-right-color
border-bottom-color
border-left-color.
![borded colors](https://dubbsong.github.io/assets/img/css-sololearn-properties-03-03.png)
* padding : The padding property allows 
you to specify how much space 
should appear between the 
content of an element and its 
border.You can specify different values 
for each side of a box using:
padding-top
padding-right
padding-bottom
padding-left.
* margin : The margin property controls 
the gap between boxes. Its value 
is commonly given in pixels, 
although you may also use 
percentages or ems.You can specify values for each 
side of a box using:
margin-top
margin-right
margin-bottom
margin-left.
* Centering Content : If you want to center a box on 
the page (or center it inside 
the element that it sits in), you 
can set the left-margin and 
right-margin to auto.
In order to center a box on the 
page, you need to set a width
for the box (otherwise it will take 
up the full width of the page).
* Hiding boxes : visibility The visibility property allows 
you to hide boxes from users 
but It leaves a space where the 
element would have been.
This property can take two 
values:
hidden
This hides the element.
visible
This shows the element.If the visibility of an element 
is set to hidden, a blank space 
will appear in its place.
* border-image : The border-image property 
applies an image to the border of 
any box. It takes a background 
image and slices it into nine 
pieces.
* box-shadows : The box-shadow property 
allows you to add a drop shadow 
around a box. It works just like 
the text-shadow property that 
you met on page 288. It must 
use at least the first of these two 
values as well as a color:Horizontal offset
Negative values position the 
shadow to the left of the box.
Vertical offset
Negative values position the 
shadow to the top of the box.
Blur distance
If omitted, the shadow is a solid 
line like a border.
Spread of shadow
If used, a positive value will 
cause the shadow to expand in 
all directions, and a negative 
value will make it contract.
* Rounded Corners : (border-radius) CSS3 introduces the ability to 
create rounded corners on any 
box, using a property called 
border-radius. The value 
indicates the size of the radius 
in pixels.
Older browsers that do not 
support this property will show a 
box with right-angled corners.
![Rounded Corners](https://www.viralpatel.net/app/uploads/2009/08/rounded-corner-css.png)
* Elliptical shapes : (border-radius) To create more complex shapes, 
you can specify different 
distances for the horizontal and 
the vertical parts of the rounded 
corners.
For example, this will create a 
radius that is wider than it is tall:You can target just one corner 
using the individual properties 
for that corner:
border-top-left-radius: 
80px 50px;.
![Elliptical shapes](https://cdn.idevie.com/wp-content/uploads/2018/10/draw-with-css-uneven-border-radius-2.png)
##  Chapter 2: Basic JavaScript Instructions
* USING QUOTES 
INSIDE A STRING : Sometimes you will want to use 
a double or single quote mark 
within a string. 
Because strings can live in single 
or double quotes, if you just 
want to use double quotes in the 
string, you could surround the 
entire string in single quotes. 
* USING A VARIABLE TO 
STORE A BOOLEAN : A Boolean variable can only have 
a value of true or fa 1 se, but this 
data type is very helpful. 
In the example on the right, the 
values true or fa 1 se are used 
in the cl ass attributes of HTML 
elements. These values trigger 
different CSS class rules: true 
shows a check, fa 1 se shows a 
cross.
* SHORTHAND FOR 
CREATING VARIABLES : Programmers sometimes use 
shorthand to create variables. 
Here are three variations of how 
to declare variables and assign 
them values: 
1. Variables are declared and 
values assigned in the same 
statement.
2. Three variables are declared 
on the same line, then values 
assigned to each. 
3. Two variables are declared 
and assigned values on the same 
line. Then one is declared and 
assigned a value on the next line. 
* CHANGING THE VALUE 
OF A VARIABLE : Once you have assigned a value 
to a variable, you can then 
change what is stored in the 
variable later in the same script. 
Once the variable has been 
created, you do not need to 
use the var keyword to assign 
it a new value. You just use the 
variable name, the equals sign 
(also known as the assignment 
operator), and the new value for 
that attribute. 
## Chapter 4: Decisions and Loops
* USING SWITCH 
STATEMENTS : In this example, the purpose 
of the switch statement is to 
present the user with a different 
message depending on which 
level they are at. The message is 
stored in a variable called msg. 
* TYPE COERCION 
& WEAK TYPING :If you use a data type JavaScript did not expect, 
it tries to make sense of the operation rather 
than report an error. 
JavaScript can convert data 
types behind the scenes to 
complete an operation. This is 
known as type coercion. For 
example, a string 'l ' could be 
converted to a number 1 in the 
following expression:(' 1' > 0). 
As a result, the above expression 
would evaluate to true. 
JavaScript is said to use weak 
typing because the data type 
for a value can change. Some 
other languages require that you 
specify what data type 
each variable will be. They are 
said to use strong typing. 
* TRUTHY & FALSY 
VALUES : Due to type coercion, every value in JavaScript 
can be treated as if it were true or false; and 
this has some interesting side effects.Falsy values are treated as if they 
are fa 1 se. The table to the left 
shows a hi ghScore variable with 
a series of values, all of which 
are falsy.Falsy values can also be treated 
as the number 0 . Truthy values are treated as if 
they are true. Almost everything 
that is not in the falsy table can 
be treated as if it were true. 
Truthy values can also be treated 
as the number 1. 
* KEY LOOP CONCEPTS : 
 1 - KEYWORDS : break 
This keyword causes the 
termination of the loop and tells 
the interpreter to go onto the 
next statement of code outside 
of the loop. (You may also see it 
used in functions.) 
continue 
This keyword tells the interpreter 
to continue with the current 
iteration, and then check the 
condition again. (If it is true, the 
code runs again.) 

2 - LOOPS & ARRAYS : Loops are very helpful when 
dealing with arrays if you want to 
run the same code for each item 
in the array. 
For example, you might want 
to write the value of each item 
stored in an array into the page. 
You may not know how many 
items will be in an array when 
writing a script, but. when the 
code runs, it can check the total 
number of items in a loop. That 
figure can then be used in the 
counter to control how many 
times a set of statements is run. 
Once the loop has run the right 
number of times, the loop stops. 

3- PERFORMANCE ISSUES : It is important to remember 
that when a browser comes 
across JavaScript, it will stop 
doing anything else until it has 
processed that script. 
If your loop is dealing with only 
a small number of items, this 
will not be an issue. If, however, 
your loop contains a lot of items, 
it can make the page slower to 
load. 
If the condition never returns 
fa 1 se, you get what is commonly 
referred to as an infinite loop. 
The code will not stop running 
until your browser runs out of 
memory (breaking your script). 
Any variable you can define 
outside of the loop and that 
does not change within the loop 
should be defined outside of it. 
If it were declared inside the 
loop, it would be recalculated 
every time the loop ran, 
needlessly using resources. 
* USING FOR LOOPS : A for loop is often used to loop 
through the items in an array. 
In this example, the scores for 
each round of a test are stored in 
an array called scores. 
The total number of items in 
the array is stored in a variable 
called arrayl ength. This 
number is obtained using the 
l ength property of the array. 
* USING WHILE LOOPS : Here is an example of awhil e 
loop. It writes out the 5 times 
table. Each time the loop is run, 
another calculation is written 
into the variable called msg. 
This loop will continue to run 
for as long as the condition in 
the parentheses is true. That 
condition is a counter indicating 
that, as long as the variable 
i remains less than 10, the 
statements in the subsequent 
code block should run. 
Inside the code block there are 
two statements: 
The first statement uses the+= 
operator, which is used to add 
new content to the msg variable. 
Each time the loop runs, a new 
calculation and line break is 
added to the end of the message 
being stored in it. So+" works as 
a shorthand for writing: 
msg = msg + 'new msg' 
(See bottom of the next page for 
a breakdown of this statement.) 
The second statement 
increments the counter variable 
by one. (This is done inside 
the loop rather than with the 
condition.) 
When the loop has finished, the 
interpreter goes to the next line 
of code, which writes the msg 
variable to the page. 
## summary 
* Conditional statements allow your code to make 
decisions about what to do next.
* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) 
are used to compare two operands. 
* Logical operators allow you to combine more than one 
set of comparison operators.
* if ... else statements allow you to run one set of code 
if a condition is true, and another if it is false. 
* switch statements allow you to compare a value 
against possible outcomes (and also provides a default 
option if none match).
* Data types can be coerced from one type to another.
* All values evaluate to either truthy or falsy.
* There are three types of loop: for, while, and 
do ... while. Each repeats a set of statements. 






