# Basics of HTML, CSS & JS summary 

HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs). <br>

**Headings:** <br>
HTML has six "levels" of headings. <br>
The contents of an < h1> element is the largest, and the contents of an < h6> element is the smallest. <br>

**Paragraphs :** <br>
To create a paragraph use the opening < p> tag and closing < /p> tag. <br>

**Bold and italic :** <br>

By enclosing words in the tags < b> and < /b> we can make characters appear bold. <br>

By enclosing words in the tags < i> and < /i> we can make characters appear italic. <br>

**Superscript & subscript :** <br>

The < sup> element is used with suffixes of dates or mathematical concepts like raising a number to a power. <br>

The < sub> element  is commonly used with foot notes or chemical formulas. <br>

**White space :** <br>

When the browser comes across two or more spaces next to each other, it only displays one space. <br>

**Line break and horizontal rules :** <br>

to add a line break inside the middle of a paragraph use  < br />. <br>

To create a break between themes use < hr /> <br>

----------------------------------------------------------------------------------------------------------------------------------------<br>

**semantic markup:** <br>

text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages. <br>

**< strong>** indicates that its content has strong importance. <br>

**< em>** indicates emphasis that subtly changes the meaning of a sentence. <br>

**< blockquote>** used for longer quotes that take up an entire paragraph. <br>

**< q>** used for shorter quotes. <br>

**< abbr>** it defines an abbreviation or an acronym. <br>

**< cite>** used when you are referencing a piece of work. <br>

**< dfn>** used to indicate the term being defined within the context of a definition phrase or sentence. <br>

**< address>** to contain contact details for the author of the page. <br>

----------------------------------------------------------------------------------------------------------------------------------------<br>              

**Introducing CSS :**  <br>

CSS works by associating rules with HTML elements that govern how the content should be displayed. <br>

A CSS rule contains two parts: a **selector** and a **declaration.** <br>

CSS declarations sit inside curly brackets and each is made up of two parts: a **property** and a **value**, separated by a **colon**. <br>

 **Ways of inserting a style sheet:** <br>
* External CSS
* Internal CSS

**External styles** are defined within the < link> element, inside the < head> section. <br>

**Internal style** is defined inside the < style> element, inside the head section. <br>

**CSS Selectors :** <br> <br>

-----------------------------------------------------------------------------------------------              
| **Selector**        | **Example**                                                           |
-----------------------------------------------------------------------------------------------                
| Universal selector. | * {} target all elements on the page.                                 |
-----------------------------------------------------------------------------------------------            
|                     |                                                                       |
| Type selector.      | h1,h2,h3 {} , target the < h1>, < h2> and < h3> elements.             |
-----------------------------------------------------------------------------------------------                                                                          
| Class selector.     | .note {}                                                              |
|                     | Targets any element whose class attribute has a value of note.        |
|                     |                                                                       |
|                     | p.note {}                                                             |
|                     | Targets only < p> elements whose class attribute has a value of note. |
|                     |                                                                       |
-----------------------------------------------------------------------------------------------              
| ID selector.        | #introduction {}                                                      |
|                     |   Targets the element whose id attribute has a value of introduction. | 
-----------------------------------------------------------------------------------------------             
| child selector.	  |  Targets any < a> elements that are children of an < li>              |
|                     |    element (but not other < a> elements                               |
|                     |     in the page).                                                     |
-----------------------------------------------------------------------------------------------              
| descendant Selector.|   p a {}                                                              |
|                     |    Targets any < a> elements that sit inside a < p> element,          |
|                     |   even if there are other elements nested between them.               |
-----------------------------------------------------------------------------------------------              
|  adjacent Sibling   |   h1+p {}                                                             |
|  Selector.          |   Targets the first < p> element after any < h1> element              |
|                     |   (but not other < p> elements).                                      |
-----------------------------------------------------------------------------------------------                                      
| general Sibling     |   h1~p {}                                                             |
|  selector.          |    If you had two < p> elements that are siblings of an < h1>         |
|                     |    element, this rule would apply to both.                            |
-----------------------------------------------------------------------------------------------                                
<br>

**Inheritance :**  <br>
is a process of receiving values of properties by a child element from its parent element. <br>

----------------------------------------------------------------------------------------------------------------------------------------              

**Basic JavaScript instructions:** <br>

A script is a series of instructions that a computer can follow one-by-one. <br>
Each individual instruction or step is known as a statement. <br>
Statements should end with a semicolon. <br>

**Comments :**  <br> 
It can be used to explain JavaScript code. <br>
It makes your code easier to read and understand. <br>

**Single line comments** start with //. <br>
**Multi-line comments** start with /* and end with */. <br>

**Variables:** <br> 
They are containers for storing data values. <br>
In order to declare a variable , first you create it then you give it a name, then you assign a value. <br>
Var is example pf what programmers called a keyword. <br>

**Data types :** <br> 
- Numeric data type (0-9).
- String data type (text).
- Boolean data type (true or false).

**Rules for naming variables :** <br>

- Names must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
- Do not use a dash(-) or a period (.) in a variable name.
- You cannot use keywords or reserved words. 
- Use a name that describes the kind of information that the variable stores. 
- If it has more than one word. Write it in camelCase. 

**Array:** <br>
Is a special type of variable. It doesn't just store one value; it stores a list of values. <br>

**Expressions :**  <br>
They evaluate into a single value. <br>
They rely on operators to calculate a value. <br>

**There are two types of expressions:** <br>
- Expression that just assign a value to a variable.
- Expression that use two or more values to return a single value. 

**Operators:** <br>

**1- Artihemtic Operators :** <br>

<img src= "Images/table.png"/> <br>

**2- String Operator :** <br>

There is just one string operator: the+ symbol. It is used to join the strings on either side of it. <br>

---------------------------------------------------------------------------------------------------------------------------------------- <br>             

**Decisions and Loops :** <br>

**There are two components to a decision :** <br>
1- An expression is evaluated; which returns a value. <br>
2- A conditional statement says what to do in a given situation. <br>

**Comparison Operators :** <br>
It return single values of "true" or "false". <br>
**"= ="** equal to. <br>
**"! ="** no equal to. <br>
**"= = ="** strict equal to. <br> 
**"! = ="** strict not equal to. <br>
**">"** greater than. <br>
**"<"** less than. <br>
**">="** greater than or equal to. <br>
**"<="** less than or equal to. <br>

**Logical Operators :** <br>
It allows you to compare the results of more than one comparison operator. <br>

**"&&"** logical and. <br>
**"||"** logical or. <br>
**"!"** logical not. <br>

**If Statements :** <br>
It evaluates or check a condition. If it is "true", any statements in the subsquent code block are executed. <br>

**If..Else Statementss :** <br>
It checks a condition. If it resloves to "true" , the first code block is executes. If the conditional resloves to "false", the second code block is run instead. <br>

---------------------------------------------------------------------------------------------------------------------------------------- <br>             





