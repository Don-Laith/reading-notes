## Introduction
####  Learning to program with JavaScript involves: 
- Understanding some basic programming concepts and the terms that JavaScript programmers use to describe them.
- Learning the language itself and, like all languages, you need to know its vocabulary and how to structure your sentences.
- Becoming familiar with how it is applied by looking at examples of how JavaScript is commonly used in websites today.

#### recipe :
##### which allows it to access or change the content of a page. For example:
- A gallery script could check which
image a user clicked on and disA gallery script could check which image a user clicked on and display a larger version of that image
- A mortgage calculator could collect values from a form, perform a ca lculation, and display repayments 
- An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport).
• A button is pressed
• A link is clicked (or tapped) on
• A cursor hovers over an element
• Information is added to a form
• An interval of time has passed
• A web page has finished loading

### html and css : a quick refresher :
####  HTML ELEMENTS 
- HTML elements are added to the content of a page to describe its structure. An element consists of the opening and closing tags, plus its content. 
- Tags usually come in pairs with an opening tag and a closing tag. There are a few empty elements with no     content,  They have one self-closing tag. 
- opening tags can carry attributes, which tell us more about that element. Attributes have a name and a value. The value is usually given in quotes. 
#### CSS RULES 
- CSS uses rules to indicate how the contents of one or more elements should be displayed in the browser. Each rule has a selector and a declaration block.
- The CSS selector indicates which element(s) the rule applies to. The declaration block contains rules that indicate how those elements should appear. 
- Each declaration in the declaration block has a property (the aspect you want to control), and a value, which is the setting for that property. 
#### The ABC of programming 
- A : What is a script and how do I create one?
- B : How do computers fit in with the world around them?
- C : How do I write a script for a web page?
## A :
- A SCRIPT IS A SERIES OF INSTRUCTIONS
#### WRITING A SCRIPT
###### To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it. Humans can achieve complex goals without thinking about them too much, for example you might be able to drive a car, cook breakfast, or send an email without a set of detailed instructions. But the first time we do these things they can seem daunting. Therefore, when learning a new skill, we often break it down into smaller tasks, and learn one of these at a time. With experience these individual tasks grow familiar and seem simpler. Some of the scripts you will be reading or writing when you have finished this book will be quite complicated and might look intimidating at first. However, a script is just a series of short instructions, each of which is performed in order to solve the problem in hand. This is why creating a script is like writing a recipe or manual that allows a computer to solve a puzzle one step at a time. It is worth noting, however, that a computer doesn't learn how to perform tasks like you or I might; it needs to follow instructions every time it performs the task. So a program must give the computer enough detail to perform the task as if every time were its first time.
### step for that :
-  DEFINE THE GOAL
- DESIGN THE SCRIPT
#### DESIGNING A SCRIPT: TASKS 
###### Once you know the goal of your script, you can work out the individual tasks needed to achieve it. This high-level view of the tasks can be represented using a flowchart.
#### Each individual task may be broken down into a sequence of steps. When you are ready to code the script, these steps can then be translated into individual lines of code. 

##### Every step for every task shown in a flowchart needs to be written in a language the computer can understand and follow.
## SUMMARY 
### THE ABC OF PROGRAMMING  
###A: What is a script and how do I create one? 
- A script is a series of instructions that the computer can follow in order to achieve a goal. 
- Each time the script runs, it might only use a subset of all the instructions.
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically
-  To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). 
## FUNCTION
#### WHAT IS A FUNCTION?
* Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
* Grouping together the The steps that the function On the right, there is an example statements that are required to needs to perform in order to of a function in the JavaScript answer a question or perform a perform its task are packaged file. It is called updateMessage() . task helps organize your code. up in a code block. You may remember from the last chapter Don't worry if you do not
- Furthermore, the statements in a that a code block consists of one understand the syntax of the function are not always executed or more statements contained example on the right; you will when a page loads, so functions within curly braces. ( And you do take a closer look at how to write also offer a way to store the steps not write a semicolon after the and use functions in the pages needed to achieve a task. The closing curly brace - like you do that follow. script can then ask the function after a statement.) to perform all of those steps as Remember that programming and when they are required. Some functions need to be languages often rely upon on
- For example, you might have provided with information in name/value pairs. The function a task that you only want to order to achieve a given task. For has a name, updateMessage, perform if the user clicks on a example, a function to calculate and the value is the code block specific element in the page. the area of a box would need (which consists of statements). to know its width and height. When you call the function by its If you are going to ask the Pieces of information passed name, those statements will run. function to perform its task to a function are known as later, you need to give your parameters. You can also have anonymous function a name. That name functions. They do not have a should describe the task it is When you write a function and name, so they cannot be called. performing. When you ask it to you expect it to provide you Instead, they are executed as perform its task, it is known as with an answer, the response is soon as the interpreter comes calling the function. known as a return value. across them.
### continues
- DECLARING FUNCTIONS THAT NEED INFORMATION 
- Sometimes a function needs specific information to perform its task. In such cases, when you declare the function you give it parameters. Inside the function, the parameters act like variables. 
- If a function needs information to work, you indicate what it needs to know in parentheses after the function name. 
- The items that appear inside these parentheses are known as the parameters of the function. Inside the function those words act like variable names.  PARAMETERS 
- function getArea(width, height) { return width * height; }
-  THE PARAMETERS ARE USED LIKE VARIABLES WITHIN THE FUNCTION 
- This function will calculate and return the area of a rectangle. To do this, it needs the rectangle's width and height. Each time you call the function these values could be different. 
- This demonstrates how the code can perform a task without knowing the exact details in advance, as long as it has rules it can follow to achieve the task.  - FUNCTIONS, METHODS & OBJECTS 
- So, when you design a script, you need to note the information the function will require in order to perform its task.  If you look inside the function, the parameter names are used just as you would use variables. Here, the parameter names width and height represent the width and height of the wall. 