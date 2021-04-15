## HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER
#### Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript
#### PROGRESSIVE ENHANCEMENT
##### These three layers form the basis of a popular
approach to building web pages called
progressive enhancement.
#### As more and more web-enabled devices come onto the market, this concept is becoming more widely adopted.

#### HTML ONLY
Starting with the HTML layer
allows you to focus on the most
important thing about your site:
its content.
Being plain HTML, this layer
should work on all kinds of
devices, be accessible to all
users, and load quite quickly on
slow connections.
#### HTML+CSS
Adding the CSS rules in a
separate file keeps rules
regarding how the page looks
away from the content itself.
You can use the same style sheet
with all of your site, making your
sites faster to load and easier
to maintain. Or you can use
different style sheets with the
same content to create different
views of the same data
#### HTML+CSS+JAVASCRIPT
The JavaScript is added last
and enhances the usability of
the page or the experience of
interacting with the site.
Keeping it separate means
that the page still works if the
user cannot load or run the
JavaScript. You can also reuse
the code on several pages
(making the site faster to load
and easier to maintain).
### CREATING A BASIC JAVASCRIPT

##### JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day.
### LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE
#####  When you want to use JavaScript with a web page, you usethe HTML <script> element to tell the browser it is coming across a script. Its sre attribute tells people where the JavaScript file is stored.

### THE SOURCE CODE IS NOT AMENDED
If you look at the source code for the example
you just created, you will see that the HTML is
still exactly the same.
### PLACING THE SCRIPT IN THE PAGE
You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files).

### HOW TO USE OBJECTS & METHODS 
This one line of JavaScript shows how to use objects and methods. Programmers refer to this as calling a method of an object. 
The document object represents the entire web page. All web browsers implement this object, and you can use it just by giving its name. 
OBJECT I I 
###  
METHOD 
document.write('Good afternoon!'); 
MEMBER OPERATOR 
The document object has several methods and properties. They are known as members of that object. 
You can access the members of an object using a dot between the object name and the member you want to access. It is called a member operator. 
Behind the scenes, the browser uses a lot more code to make the words appear on the screen, but you don't need to know how the browser does this. 
50 THE ABC OF PROGRAMMING 
PARAMETERS 
Whenever a method requires some information in order to work, the data is given inside the parentheses. 
Each piece of information is called a parameter of the method. In this case, the write() method needs to know what to write into the page. 
You only need to know how to call the object and method, and how to tell it the information it needs to do the job you want it to. It will do the rest. 
There are lots of objects like the document object, and lots of methods like the write() method that will help you write your own scripts. 
## summary
#### how do i write a code:
#### It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension. 
#### " The HTML <script> element is used in HTML pages  to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).
#### If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.
### STATEMENTS
##### A script is a series of instructions that a computer can follow one-by-one.
#####Each individual instruction or step is known as a statement. Statements should end with a semicolon.
###### JAVASCRIPT IS CASE SENSITIVE
##### JavaScript is case sensitive so hourNow means something different to HourNow or HOURNOW

### comments 
### You should write comments to explain what your code does. They help make your code easier to read and understand.This can help you and others who read your code
### MULTI-LINE COMM ENTSTo write a comment that stretches over more thanone line, you use a multi-line comment, starting withthe "/*" characters and ending with the * / characters.Anything between these characters is not processed·by the JavaScript interpreter.Multi-line comments are often used for descriptions of how the script works, or to prevent a section of the script from running when tes ting it.


## variable how to declay them
##### HOW TO USE OBJECTS & METHODS 
This one line of JavaScript shows how to use objects and methods. Programmers refer to this as calling a method of an object. 
The document object represents the entire web page. All web browsers implement this object, and you can use it just by giving its name. 
OBJECT I 
### The write() method of the document object allows new content to be written into the page where the <scri pt> element sits. 
### METHOD 
document.write('Good afternoon!'); 
MEMBER OPERATOR 
PARAMETERS 
VARIABLES: HOW TO DECLARE THEM 
Before you can use a variable, you need to announce that you want to use it. This involves creating the variable and giving it a name. Programmers say that you declare the variable. 
### DATA type
#### JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans.
NUMERIC DATA TYPE
The numeric data type handles
numbers.
0.75
For tasks that involve counting
or calculating sums, you will
use numbers 0-9. For example,
five thousand, two hundred and
seventy-two would be written
5272 (note there is no comma
between the thousands and
the hundreds). You can also
have negative numbers (such
as -23678) and decimals (three
quarters is written as 0.75).
Numbers are not only used for
things like calculators; they
are also used for tasks such
as determining the size of the
screen, moving the position of
an element on a page, or setting
the amount of time an element
should take to fade in.
@ BASIC JAVASCRIPT INSTRUCTIONS
STRING DATA TYPE
The strings data type consists of
letters and other characters.

### Note how the string data type is
enclosed within a pair of quotes.
These can be single or double
quotes, but the opening quote
must match the closing quote.
Strings can be used when
working with any kind of text.
They are frequently used to add
new content into a page and they
can contain HTML markup.
BOOLEAN DATA TYPE
Boolean data types can have one
of two values: true or false.
true
It might seem a little abstract at
first, but the Boolean data type is
actually very helpful.
You can think of it a little like a
light switch - it is either on or off.
As you will see in Chapter 4,
Booleans are helpful when
determining which part of a
script should run.






