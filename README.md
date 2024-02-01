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

To make things easier, you can use the <code4>&ltq&gt</code4> element in HTML, which stands for quote and the browser will automatically provide the appropriate quote marks for you.
Date  and Time Inputs
For date and time HTML uses a single element called <code4>&lttime&gt</code4>. This element can be used to mark anything that specifies a time of day, or a duration.
It consists of an opening tag <code4>&ltimee&gt</code4> and a closing tag <code4>&lttime&gt</code4>.
For example "<time>May 8th</time>" or "<time>May 8th 2025</time>"
The datetime attribute allows us to specify the date or time in a format that computers can understand.It is written like this: "<time datetime="2025-05-08">May 8, 2025</time>".

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

ARIA roles
ARIA Roles are like extra attribute that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. 
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to  ensure a website is fully accessible.







