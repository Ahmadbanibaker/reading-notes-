# HTML & CSS Design and Build Websites JAVASCRIPT & JQUERY
## Chapter 6: Tables
* What's a Table?
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.
* Basic Table Structure
< table >
The < table> element is used
to create a table. The contents
of the table are written out row
by row.
< tr>
You indicate the start of each
row using the opening < tr> tag.
(The tr stands for table row.)
It is followed by one or more
< td> elements (one for each cell
in that row).
At the end of the row you use a
closing < /tr> tag.
< td>
Each cell of a table is
represented using a < td>
element. (The td stands for
table data.)
At the end of each cell you use a
closing < /td> tag.
* Table Headings 
< th>
The <th> element is used just
like the < td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
Even if a cell has no content,
you should still use a < td> or
< th> element to represent
the presence of an empty cell
otherwise the table will not
render correctly. (The first cell
in the first row of this example
shows an empty cell.)
* Spanning ColumnS 
Sometimes you may need the
entries in a table to stretch
across more than one column.
The colspan attribute can be
used on a < th> or < td> element
and indicates how many columns
that cell should run across.
* Spanning rows 
You may also need entries in
a table to stretch down across
more than one row.
The rowspan attribute can be
used on a < th> or < td> element
to indicate how many rows a cell
should span down the table.
* Long Tables 
< thead>
The headings of the table should
sit inside the < thead> element.
< tbody>
The body should sit inside the
< tbody> element.
< tfoot>
The footer belongs inside the
< tfoot> element.
* Width & Spacing 
There are some outdated
attributes which you should not
use on new websites. You may,
however, come across some
of them when looking at older
code, so I will mention them
here. All of these attributes have
been replaced by the use of CSS.
* Border & Background 
The border attribute was used
on both the < table> and < td>
elements to indicate the width of
the border in pixels.
The bgcolor attribute was used
to indicate background colors
of either the entire table or
individual table cells. The value
is usually a hex code (which we
discuss on pages 249-252).
This example uses the HTML
border and bgcolor attributes.
No CSS attributes were utilized
in this example. 
### summary 
* The < table> element is used to add tables to a web
page.
* A table is drawn out row by row. Each row is created
with the < tr> element.
* Inside each row there are a number of cells
represented by the < td> element (or < th> if it is a
header).
* You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
* For long tables you can split the table into a < thead>,
< tbody>, and < tfoot>.

## Chapter 3: Functions, Methods, and Objects
* WHAT IS AN OBJECT? 
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 
* ADDING AND REMOVING
PROPERTIES 
Once you have created an object
(using literal or constructor
notation), you can add new
properties to it.
You do this using the dot
notation that you saw for adding
properties to objects on pl03.
In this example, you can see that
an instance of the hotel object
is created using an object literal.
* THIS (IT IS A KEYWORD)
The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates. 
* STORING DATA 
In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 
If you want to access items via a property name or key, use an object
(but note that each key in the object must be unique).
If the order of the items is important, use an array. 
* DATA TYPES REVISITED 
In JavaScript there are six data types:
Five of them are described as simple (or primitive) data types.
The sixth is the object (and is referred to as a complex data type). 
1. String
2. Number
3. Boolean
4. Undefined (a variable that has been declared, but
no value has been assigned to it yet)
5. Null (a variable with no value - it may have had
one at some point, but no longer has a value)
### summary
* Functions allow you to group a set of related
statements together that represent a single task. 

* Functions can take parameters (informatiorJ required
to do their job) and may return a value. 

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

