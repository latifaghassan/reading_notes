<h1> Introductory HTML and JavaScript summary: </h1>

<div>
**Structure:** 

We use structure when we writing web pages.

To describe the structure of a web page, we add code to the words we want to appear on the page.

The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. 

Elements are usually made up of two tags: an opening tag and a closing tag. 

**Tags :**

Tags are often referred to as elements.

Tags usually come in pairs. 

The opening tag denotes the start of a piece of content; the closing tag denotes the end.

Opening tags can carry attributes, which tell us more about the content of that element.

Attributes require a name and a value.

The page contains a “head, title, body”. 

**HTML :** 

HTML stands for HyperText Markup Language. 

To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.

**DOCTYPE :** 

It tells a browser which version of HTML the page is using 

**Comments in HTML :** 

If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
‏ < !-- comment goes here -->

**id attribute:** 

It is used to uniquely identify that element from other elements on the page.

It is important that no two elements on the same page have the same value for their id attributes. 

The id attribute is known as a global attribute because it can be used on any element.

**Class attribute :** 

Is used to identify several elements as being different from the other elements on the page.

**Block elements:** 

It always appear to start on a new line in the browser window.

Examples of block elements are
 < h1>, < p>, < ul>, and < li>.

**Inline elements:** 

It appear to continue on the same line as their neighbouring elements. 

Examples of inline elements are
 < a>, < b>, < em>, and < img>.

**Grouping text & elements in a block:**

**< div>**
The < div> element allows you to group a set of elements together in one block-level box.

**Grouping text & elements inline:**

The < span> element, which is an inline element. It paragraph correctly renders as a single, unbroken text flow.

**< iframe>**
An iframe is like a little window that has been cut into your page, and in that window you can see another page. The term iframe is an abbreviation of inline frame.

**< meta> :**

The < meta> tag allows you to supply all kinds of information about your web page. It is not visible to users but fulfills a number of purposes such as telling search engines about your page.  is an empty element so it does not have a closing tag.

**Escape Characters:** 

Escape characters are used to include special characters in your pages such as <, >, and ©.
</div>
.....................................................................................................................................

<div>

**HTML5 layouts:** 

The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.

the < header> element used to contain the site name and the main navigation. 

The < footer> element contains copyright information, along with links to the privacy policy and terms and conditions.

The < article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

The < aside> element has two purposes, depending on whether it is inside an < article> element or not. When the < aside> elements used inside an < article> element, it should contain information that is related to the article. When the < aside> element is used outside of an < article> element, it acts as a container for content that is related to the entire page. 

The < section> element groups related content together, and typically each section would have its own heading. it may contain several distinct < article> elements that have a common theme or purpose.

The purpose of the < hgroup> element is to group together a set of one or more < h1> through < h6> elements so that they are treated as one single heading.

the < figure> It can be used to contain any content that is referenced from the main flow of an article. Examples of usage include: Images/ Videos /Graphs / Diagrams / Code samples. 
The < figure> element should also contain a < figcaption> element which provides a text decription for the content of the < figure> element.

the < div> element will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.

Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.

</div>

.....................................................................................................................................

<div>

**Process & Design:** 

**When you are creating a new website;  three questions should be answered;** 

1- Who is the site For?
2- Why people visit your page? 
3- What your visitors are trying to achieve? 
4- What information your visitors need? 
5- How often people with visit your site? 

**Site Maps :** 
It allows you to plan the structure of a site.
 

**WireFrames:** 

It allows you to organize the information that will need to go on each page.


**Getting your message across using Design:** 

Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.

You can differentiate between pieces of information using size, color, and style.

You can use grouping and similarity to help simplify the information you present.

</div>

.....................................................................................................................................

<div>

**The ABC of programming:** 

What is “script” and how do I create one ? 

Script is a series of instructions that a computer can follow to achieve a goal.

Each time the script runs, it might only use a subset of all the instructions.

Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.

To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).

**HOW A BROWSER SEES A WEB PAGE ?** 
1- The browser receive an HTML page.
2- It creates a model of the page and stores it in memory. 
3- It shows the page on screen using a rendering engine. 

**HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER?** 

**HTML :** content layer.
**CSS :** presentation layer.
**JAVASCRIPT :** behaviour layer.

These three layers form the basis of a popular approach to building web pages called progressive enhancement.

**CREATING A BASIC JAVASCRIPT:**

JavaScript is written in plain text, just like HTML and CSS

When you want to use JavaScript with a web page, you use the HTML < script> element to tell the browser it is coming across a script.

It is best to keep JavaScript code in its own JavaScript file. but they have the . j s extension.

</div>