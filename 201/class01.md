<h1> Introductory HTML and JavaScript summary: </h1>

**Structure:**<br> 

We use structure when we writing web pages.<br> 

To describe the structure of a web page, we add code to the words we want to appear on the page.<br> 

The HTML code is made up of characters that live inside angled brackets — these are called HTML elements.<br> 

Elements are usually made up of two tags: an opening tag and a closing tag.<br>  

**Tags :** <br> 

Tags are often referred to as elements.<br> 

Tags usually come in pairs.<br> 

The opening tag denotes the start of a piece of content; the closing tag denotes the end.<br> 

Opening tags can carry attributes, which tell us more about the content of that element.<br> 

Attributes require a name and a value.<br> 

The page contains a “head, title, body”.<br>  

**HTML :** <br> 

HTML stands for HyperText Markup Language. <br> 

To learn HTML you need to know what tags are available for you to use, what they do, and where they can go. <br> 

**DOCTYPE :** <br> 

It tells a browser which version of HTML the page is using. <br>  

**Comments in HTML :** <br> 

If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters: <br> 

‏ < !-- comment goes here --><br> 

**id attribute:** <br> 

It is used to uniquely identify that element from other elements on the page. <br> 

It is important that no two elements on the same page have the same value for their id attributes. <br> 

The id attribute is known as a global attribute because it can be used on any element. <br> 

**Class attribute :** <br> 

Is used to identify several elements as being different from the other elements on the page. <br> 

**Block elements:** <br> 

It always appear to start on a new line in the browser window. <br> 

Examples of block elements are <br> 
 < h1>, < p>, < ul>, and < li>. <br> 

**Inline elements:** <br> 

It appear to continue on the same line as their neighbouring elements. <br> 

Examples of inline elements are <br> 
 < a>, < b>, < em>, and < img>. <br> 

**Grouping text & elements in a block:** <br> 

**< div>** <br> 

The < div> element allows you to group a set of elements together in one block-level box. <br> 

**Grouping text & elements inline:** <br> 

The < span> element, which is an inline element. It paragraph correctly renders as a single, unbroken text flow. <br> 

**< iframe>** <br> 

An iframe is like a little window that has been cut into your page, and in that window you can see another page. The term iframe is an abbreviation of inline frame. <br> 

**< meta> :** <br> 

The < meta> tag allows you to supply all kinds of information about your web page. It is not visible to users but fulfills a number of purposes such as telling search engines about your page.  is an empty element so it does not have a closing tag. <br> 

**Escape Characters:** <br> 

Escape characters are used to include special characters in your pages such as <, >, and ©.<br> 
 
.....................................................................................................................................

**HTML5 layouts:** <br> 

The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure. <br> 

the < header> element used to contain the site name and the main navigation. <br>  

The < footer> element contains copyright information, along with links to the privacy policy and terms and conditions. <br> 

The < article> element acts as a container for any section of a page that could stand alone and potentially be syndicated. <br> 

The < aside> element has two purposes, depending on whether it is inside an < article> element or not. When the < aside> elements used inside an < article> element, it should contain information that is related to the article. When the < aside> element is used outside of an < article> element, it acts as a container for content that is related to the entire page. <br> 

The < section> element groups related content together, and typically each section would have its own heading. it may contain several distinct < article> elements that have a common theme or purpose. <br> 

The purpose of the < hgroup> element is to group together a set of one or more < h1> through < h6> elements so that they are treated as one single heading. <br> 

the < figure> It can be used to contain any content that is referenced from the main flow of an article. Examples of usage include: Images/ Videos /Graphs / Diagrams / Code samples. The < figure> element should also contain a < figcaption> element which provides a text decription for the content of the < figure> element. <br> 

the < div> element will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated. <br> 

Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements. <br> 

.....................................................................................................................................

**Process & Design:** <br> 

**When you are creating a new website;  three questions should be answered;** <br>  

1- Who is the site For? <br> 
2- Why people visit your page? <br> 
3- What your visitors are trying to achieve? <br> 
4- What information your visitors need? <br> 
5- How often people with visit your site? <br> 

**Site Maps :** <br> 
It allows you to plan the structure of a site. <br> 
 

**WireFrames:** <br> 

It allows you to organize the information that will need to go on each page. <br> 


**Getting your message across using Design:** <br> 

Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them. <br> 

You can differentiate between pieces of information using size, color, and style. <br> 

You can use grouping and similarity to help simplify the information you present. <br> 

.....................................................................................................................................

**The ABC of programming:** <br> 

**What is “script” and how do I create one ?** <br>  

Script is a series of instructions that a computer can follow to achieve a goal. <br> 

Each time the script runs, it might only use a subset of all the instructions. <br> 

Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically. <br> 

To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). <br> 

**HOW A BROWSER SEES A WEB PAGE ?** <br> 
1- The browser receive an HTML page. <br> 
2- It creates a model of the page and stores it in memory. <br> 
3- It shows the page on screen using a rendering engine. <br> 

**HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER?** <br> 

**HTML :** content layer. <br> 
**CSS :** presentation layer. <br> 
**JAVASCRIPT :** behaviour layer. <br> 

These three layers form the basis of a popular approach to building web pages called progressive enhancement. <br> 

**CREATING A BASIC JAVASCRIPT:** <br> 

JavaScript is written in plain text, just like HTML and CSS. <br> 

When you want to use JavaScript with a web page, you use the HTML < script> element to tell the browser it is coming across a script. <br> 

It is best to keep JavaScript code in its own JavaScript file. but they have the . j s extension. <br> 
