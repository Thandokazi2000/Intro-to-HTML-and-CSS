# Intro-to-HTML-and-CSS

HTML stands for Hypertext Markup Language 
It is a coding language that is used in websites, apps and various software whenever web technology is involved. Html gives structure to a website and you can specify what content appears and where, that includes placing text,images,videos,audio, forms, and interactive experiences.

CSS
The Cascading Style Sheet allows you to decorating the foundational elements of a site that you built using HTML and make your content more visually appealing.It provides you with different colors, fonts, and sizes. It also allows you to add more cool animations and interactions to make it more attractive.

JavaScripts
Javascripts adds interactivity and dynamics behaviors to websites. It can be fragile for instance if there is an error on your code or it does not understand the code it will refuse to run the code.

<h3>HTML Text Formatting</h3>

<h4>HTML Paragraphs</h4>
It uses tags, which are enclosed by the angle brackects, to mark different elements. Tags come in pairs, an opening tags and closing tags. For example the opening tag for a paragraph is <p> and the closing tag is </p>.Tags work together to define elements, Some elements like paragraphs reqiure both an opening and a closing tag, while some do not.
HTML Headlines
Web pages usually contain various titles, headlines, and subheadings. The HTML elements used for marking up headlines come in six different types:h1,h2,h,h4,h5, and h6.
The headlines elements are used to to divide the content into smaller, more digestible chunks and that make it easy to understand the structure of the page.

<h4>HTML Bold and Italics</h4>
There are four HTML elements related to this , two for bold and two for italic.
For italics in HTML we use the, <code>&lti&gt</code> element to apply visual italics and the <code4>&ltem&gt</code4> element to add emphasis.They may loook exactly the same visually, but they serve different purposes.
We have two elememts to emphasize or make something bold in HTML.
The first one is the <code4>&ltstrong&gt</code4> element, which is is used to show importance seriousness, or urgency.
on the other hand, <code4>&ltb&gt</code4> element is is more generic and neutral.
It allows you to make something bold visually, its does not carry any specific meaning or any alternative voice or mood.

<h4>HTML Lists</h4>
There are three types of lists in HTML: unordered lists, ordered list, and definition lists.
The most commonly used listing type is the unordered lists.
Each item in the list is enclosed in a <code4>&ltli&gt</code4> element, which represent a list item.
For unordered list all items are wrapped in a <code4>&ltul&gt</code4> element.
It makes  your code more readable, indent the list by adding some spaces or tabs before each one.But this indentation does not affect how the webpage looks.
To display the list with numbered steps and to show the order clearly we use the ordered list.<code4>&ltol&gt</code4> element is used to wrap the list items instead of using <code4>&ltul&gt</code4> element.
These listing types are quite similar except for the wrapping element they use.

There is also  Definition lists which is used when creating a list that resembles a key-value pair in computer science. Instead of just items, it allows you to have terms and their corresponding descriptions.
The term or key is enclosed in a <code4>&ltdt&gt</code4> tag, which stands for definition term and the description or value is enclosed in a <code4>&ltdd&gt</code4> tag, which stands for difinition description.
You can have many description for each term by using multiple <code4>&ltdd&gt</code4> tags and the entire list is wrapped in a <code4>&ltdl&gt</code4> tag, representing the definition list.

<h4>HTML Qoutes</h4>
The block quote element is used to distinguish the quote from the surrounding text, you can wrap the whole thing in a <code4>&ltblockquote&gt</code4> element. To attribute the quote <code4>&ltcite&gt</code4> elememnt is used.

To make things easier, you can use the ``` <q> ``` element in HTML, which stands for quote and the browser will automatically provide the appropriate quote marks for you.
Date  and Time Inputs
For date and time HTML uses a single element called ``` <time> ```. This element can be used to mark anything that specifies a time of day, or a duration.
It consists of an opening tag  and a closing tag ``` <time> ```.
For example ``` "<time>May 8th</time> ``` or ``` "<time>May 8th 2025</time>" ```
The datetime attribute allows us to specify the date or time in a format that computers can understand.It is written like this: 
```
"<time datetime="2025-05-08">May 8, 2025</time>".
```

<h4>HTML Code, pre, br </h4>
Pre and code elements are 

<h4>HTML Superscripts, Subscripts and small Text</h4>
Superscripts,subscript and small text are used when you need to mark up certain bits of content as having a different meaning than the rest.
Suscripts are characters that are set below the normal baseline for text.
Superscripts are characters that are set above the normal baseline of text.


<h3>HTML Capabilities</h3>

<h4>Troubleshooting and Debugging HTML Code</h4>
For troubleshooting and Debugging we open the developer tools by right-clicking to see the error.
We can use the HTML inspector in the developer tools to debug mistakes.


<h4>HTML Attributes</h4>
Class attribute is the most commonly used and it allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.
There is also an ID attribute which is similar to class attribute, but we can only use unique names once on an entire HTML page.They are used to target CSS.They are also useful when addressing specific elements in Javascript or targeted links.
The four most important Global Attributes: "class," "id," "lang," and "dir".

ARIA roles
ARIA Roles are like extra attribute that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. 
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to  ensure a website is fully accessible.

<h3>Navigation and Linking</h3>

HTML Links

When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference.
The A element is inline and can be placed within a paragraph or any other text

 <h3>Graphics and images</h3>
 IMG element to define an image
 There are four attributes that need to be included for every image.
 1.Source attribute(SRC), to define the URL of the image
 2.lternative attribute(ALT), to define an alternative text for an image, if it cannot be 
 displayed.
 3.Width and height attribute, which determine the size of the image.
 
 image formats
 GIF
 SVG-perfect for logos,icons and other types of illustrations.
 JPG
 PNG

 Figcaption defines a caption for a figure element
 Figure element to mark up a photo in a document

 <h3>Working With Media</h3>
 
 Audio element is used to play an audio file on a web page
 The controls attribute adds audio controls like play, pause, and volume.
 The source element allows you to specify alternative audio files which the browser may 
 choose from
 Video element is used to show a video on a web page
 video	Defines a video or movie
 source	Defines multiple media resources for media elements, such as video and audio
 track	Defines text tracks in media play
 
 Embedding Media via Iframes
 Embedding refers to taking content from one site and placing it within the middle of 
 another 
 sites page.E.g Google Maps, code demo or videos from youtube.

 <h3>Content Identification</h3>
 
HTML Generic Elements, Div and Span

A block-level element always starts on a new line and takes up the full width available
An inline element does not start on a new line and it only takes up as much width as necessary
The div element is a block-level and is often used as a container for other HTML elements
The span element is an inline container used to mark up a part of a text, or a part of a document

<h3>HTML integration</h3>
The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way, it is like the headquarters for getting the page off to a good start.

<h3>Forms Fundamentals</h3>
An HTML form is used to collect user input. The user input is most often sent to a server for processing.
The form element is a container for different types of input elements, such as:Text, fields, checkboxes, radio buttons, submit buttons, etc.
1.The HTML form element is used to create an HTML form for user input
2.The HTML input element is the most used form element.
3.The input type="text" defines a single-line input field for text input.
4.The label tag defines a label for many form element
5.The for attribute of the label tag should be equal to the id attribute of the input element to bind them together.
5. The input type= "submit" defines a button for submitting the form data to a form-handler

<h3>Organizing Tabular Information</h3>
HTML tables allow web developers to arrange data into rows and columns.
table element define a table
tr stands for table row
td stands for table data
th stands for table header

# Cascading Style Sheets
What is CSS?
CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media
CSS saves a lot of work. It can control the layout of multiple web pages all at once
External stylesheets are stored in CSS files

Why Use CSS?
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

CSS components
Selector
property
value
Declaration includes a CSS property name and value
CSS Selectors
CSS selectors are used to "find" (or select) the HTML elements you want to style.
A CSS rule consists of a selector and a declaration block.

E.G. Paragraph element
p is a selector in CSS (it points to the HTML element you want to style: <p>).
color is a property, and red is the property value
text-align is a property, and center is the property value


CSS selector

A CSS selector selects the HTML element(s) you want to style.
The declaration block contains one or more declarations separated by semicolons.
Each declaration includes a CSS property name and a value, separated by a colon.
Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.
We can divide CSS selectors into five categories:

Simple selectors - select elements based on name, id, class
Combinator selectors - select elements based on a specific relationship between them
Pseudo-class selectors - select elements based on a certain state
Pseudo-elements selectors - select and style a part of an element
Attribute selectors - select elements based on an attribute or attribute value

The CSS element Selector
The element selector selects HTML elements based on the element name.

The CSS id Selector
The id selector uses the id attribute of an HTML element to select a specific element.
The id of an element is unique within a page, so the id selector is used to select one unique element!
To select an element with a specific id, write a hash (#) character, followed by the id of the element.

The CSS class Selector
The class selector selects HTML elements with a specific class attribute.
To select elements with a specific class, write a period (.) character, followed by the class name.

The CSS Universal Selector
The universal selector (*) selects all HTML elements on the page.

The CSS Grouping Selector
The grouping selector selects all the HTML elements with the same style definitions.
We can combine them using a comma: p,li{property name and value}
It will be better to group the selectors, to minimize the code.
To group selectors, separate each selector with a comma.

CSS Margins
Margins are used to create space around elements, outside of any defined borders.

# Intro-to-JavaScript
JavaScript to program the behavior of web pages.

<h3>JavaScript Functions and Events</h3>
A JavaScript function is a block of JavaScript code, that can be executed when "called" for.
For example, a function can be called when an event occurs, like when the user clicks a button.
You can place any number of scripts in an HTML document.
Scripts can be placed in the body, or in the head section of an HTML page, or in both.

<h3>External JavaScript Advantages</h3>
Placing scripts in external files has some advantages:
 1.It separates HTML and code
 2.It makes HTML and JavaScript easier to read and maintain
 3.Cached JavaScript files can speed up page loads

<h3>JavaScript Display Possibilities</h3>
JavaScript can "display" data in different ways:

Writing into an HTML element, using innerHTML.
Writing into the HTML output using document.write().
Writing into an alert box, using window.alert().
Writing into the browser console, using console.log().

JavaScript Programs
A computer program is a list of "instructions" to be "executed" by a computer.
In a programming language, these programming instructions are called statements.
A JavaScript program is a list of programming statements.

JavaScript Statements
JavaScript statements are composed of:
Values, Operators, Expressions, Keywords, and Comments.
This statement tells the browser to write "Hello Dolly." inside an HTML element with id="demo":

JavaScript Values
The JavaScript syntax defines two types of values:

Fixed values
Variable values
Fixed values are called Literals.
Variable values are called Variables.

JavaScript Variables
In a programming language, variables are used to store data values.
JavaScript uses the keywords var, let and const to declare variables.
An equal sign is used to assign values to variables.

JavaScript Operators
JavaScript uses arithmetic operators ( + - * / ) to compute values:
JavaScript uses an assignment operator ( = ) to assign values to variables:

JavaScript Expressions
An expression is a combination of values, variables, and operators, which computes to a value.
The computation is called an evaluation.
For example, 5 * 10 evaluates to 50:
5 * 10

JavaScript Keywords
JavaScript keywords are used to identify actions to be performed.
The let keyword tells the browser to create variables:
The var keyword also tells the browser to create variables:

JavaScript Comments
Not all JavaScript statements are "executed".
Code after double slashes // or between /* and */ is treated as a comment.

Week 4- Day 1
JavaScript Loops
Loops are handy, if you want to run the same code over and over again, each time with a different value.

The For Loop
The for statement creates a loop with 3 optional expressions
Expression 1 is executed (one time) before the execution of the code block.
Expression 2 defines the condition for executing the code block.
Expression 3 is executed (every time) after the code block has been executed.

The For In Loop
The JavaScript for in statement loops through the properties of an Object
Example Explained
The for in loop iterates over a person object
Each iteration returns a key (x)
The key is used to access the value of the key
The value of the key is person[x]

# Node.js

Node.js is an open source server environment.
Node.js allows you to run JavaScript on the server.
Node.js uses asynchronous programming!

Here is how Node.js handles a file request:

1.Sends the task to the computer's file system.
2.Ready to handle the next request.
3.When the file system has opened and read the file, the server returns the content to the client.
Node.js eliminates the waiting, and simply continues with the next request.
Node.js runs single-threaded, non-blocking, asynchronous programming, which is very memory efficient.

What Can Node.js Do?
Node.js can generate dynamic page content
Node.js can create, open, read, write, delete, and close files on the server
Node.js can collect form data
Node.js can add, delete, modify data in your database

What is a Node.js File?
Node.js files contain tasks that will be executed on certain events
A typical event is someone trying to access a port on the server
Node.js files must be initiated on the server before having any effect
Node.js files have extension ".js"

What is a Module in Node.js?
Consider modules to be the same as JavaScript libraries.
A set of functions you want to include in your application.

Node.js as a File Server
The Node.js file system module allows you to work with the file system on your computer.
To include the File System module, use the require() method: var fs = require('fs');

Common use for the File System module:

Read files
Create files
Update files
Delete files
Rename files

Read Files
The fs.readFile() method is used to read files on your computer.
Assume we have the following HTML file (located in the same folder as Node.js):

Create Files
The File System module has methods for creating new files:
fs.appendFile()
fs.open()
fs.writeFile()
The fs.appendFile() method appends specified content to a file.


Update Files
The File System module has methods for updating files:
fs.appendFile()
fs.writeFile()
The fs.appendFile() method appends the specified content at the end of the specified file

Delete Files
To delete a file with the File System module,  use the fs.unlink() method.
The fs.unlink() method deletes the specified file

Rename Files
To rename a file with the File System module,  use the fs.rename() method.
The fs.rename() method renames the specified file

What is NPM?
NPM is a package manager for Node.js packages, or modules if you like.
www.npmjs.com hosts thousands of free packages to download and use.
The NPM program is installed on your computer when you install Node.js

What is a Package?
A package in Node.js contains all the files you need for a module.
Modules are JavaScript libraries you can include in your project.


