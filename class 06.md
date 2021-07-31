# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 3: Object Literals
* WHAT ARE BUILT-IN
OBJECTS?
Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages. 
* USING THE BROWSER
OBJECT MODEL 
1. Two of the window object's
properties, i nnerWi dth and
i nnerHei ght, show width and
height of the browser window. 
2. Child objects are stored as
properties of t heir parent object.
So dot notation is used to access
them, just like you would access
any other property of that object
3. The element whose id
attribute has a value of info is
selected, and the message that
has been built up to this point is
written into the page.
* THE DOCUMENT OBJECT 
The topmost object in the Document Object Model (or DOM) is the
document object. It represents the web page loaded into the current
browser window or tab. You meet its child objects in Chapter 5. 
* STRING O BJECT
Whenever you have a value that is a string, you can use the properties
and methods of the String object on that value. This example stores the
phrase "Home sweet home " in a variable. 
* NUMBER OBJECT
Whenever you have a value that is a number,
you can use the methods and properties of the
Number object on it
* WORKING WITH
DECIMAL NUMBERS 
1. In this example, a number
is stored in a variable called
ori ginalNumber, and it isthen
rounded up or down using two
different techniques. In both cases, you need to
indicate how many digits
you want to round to. This is
provided as a parameter in the
parentheses for that method. 
* MATH OBJECT 
The Math object has properties and methods
for mathematical constants and functions. 
### summary
* An object is a series of variables and functions that
represent something from the world around you. 
* In an object, variables are known as properties of the
object; functions are known as methods of the object. 
* Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window. 
* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts. 
* Arrays and objects can be used to create complex data
sets (and both can contain the other). 
## Chapter 5: Document Object Model
* THE DOM TREE IS A
MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes. 
* WORKING WITH
THE DOM TREE
Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 
* LOOPING THROUGH
A NODELIST 
If you want to apply the same
code to numerous elements,
looping through a Nodelist is a
powerful technique. It involves finding out how many
items are in the Nodelist, and
then setting a counter to loop
through them, one-by-one.
Each time the loop runs, the
script checks that the counter
is less than the total number of
items in the Nodelist.
* TRAVERSING THE DOM
When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM. 
* WHITESPACE NODES
Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements. 
* Fl RST & LAST CH I LD
These properties also return
inconsistent results if there is
whitespace between elements.
In this example, a slightly
different solution is used in the
HTML - the closing tags are put next to the opening tags of
the next element, making it
a little more readable. The
example starts by using the
getElementsByTagName()
method to select the < ul> element from the page. From this
element node, the fi rstChi 1 d
property will return the first <1 i >
element, and the 1 as tChi 1 d
property will return the last < l i >
element.  
### summary
* The browser represents the page using a DOM tree. 
* DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes. 

* You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax. 

* Whenever a DOM query can return more than one
node, it will always return a Nadel i st. 
* From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques. 

* An element node can contain multiple text nodes and
child elements that are siblings of each other. 
* In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery). 
* Browsers offer tools for viewing the DOM tree . 

