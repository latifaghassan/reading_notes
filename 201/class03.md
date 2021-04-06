# HTML Lists, CSS Boxes, JS Control Flow summary :

**Lists:** <br>
There are three types of HTML lists: **ordered**, **unordered**, and **definition**. <br>

**Ordered lists** use numbers.  <ol> <br>
**Unordered lists** use bullets. <ul> <br>
------------------------------------------------------------------------------------------ <br> 

 **Definition lists** are used to define terminology. <br>

<dt> is used to contain the definition term. <br>
<dl> is used when we want to create a definition list. <br>
<dd> is used to contain the definition. <br>
------------------------------------------------------------------------------------------ <br>  
Lists can be nested inside one another. <br>
------------------------------------------------------------------------------------------ <br> 
 

**Boxes :** <br>

**Box dimensions** : width , height. <br>
**Limiting width** : min-width , max-width. <br>
**Limiting height** : min-height , max-height. <br>
------------------------------------------------------------------------------------------ <br> 
 

**Overflow content:** <br> 
- When the content is larger than the box itself. <br> 
- We use “overflow: hidden” to hide any extra content. <br>
- If you want the user to scroll to see the missing content use “overflow: scroll”. <br>

**Every box has three variable properties:** <br> 

- **border** : it separated the edge of one box from another. <br> 
- **margin** : it is outside of the edge of the border. <br> 
- **padding** : it is the space between the border of a box and any content within it. <br>
------------------------------------------------------------------------------------------ <br> 
**White space** : the space between items on a page. <br>
------------------------------------------------------------------------------------------ <br> 
**Border :** <br>

|                     |  **properties**        | **Values**                                                           |
----------------------|------------------------------------------------------------------------                                                                                     
|**Border-width**|  - border-top-width |                                                        |
|               |  - border-right-width | The value of this property can either be given in pixels or using these values ( thin, medium, thick) |                           
|               |  - border-bottom-width |                                                     |
|               |  - border-left-width |                                                       |                                                                            
|               |                      |                                                       |                                                                                   
| **Border style**|   - border-top-style |                                                       |
|               |   - border-left-style | The values can be ; ( solid, dotted, dashed, double, groove, ridge, inset, outset, hidden/none.|
|               |   - border-right-style |                                                     |
|               |   -border-bottom-style |                                                     |
|               |                       |                                                       |                                                                        
| **Border color**|   - border-top-color |                                                       |
|               |   - border-right-color | The values can be ; ( RGB values, hex codes or css color names).| 
|               |   - border-bottom-color |                                                    |
|               |   -border-left-color |                                                       |
|               |                      |                                                       |                                                                                       
| **Padding**|   - padding-top |                                                            |
|               |   - padding-right | You can use pixels with those. or % |
|               |   - padding-bottom |                                                         |
|               |   -padding-left |                                                            |
|               |                 |                                                            |
| **Margin**|   - margin-top |                                                             |
|               |   - margin-right | You can use pixels with those. or % |
|               |   - margin-bottom |                                                          |
|               |   - margin-left |                                                            |                                                

------------------------------------------------------------------------------------------ <br> 

**Centering:** <br>
If you want centering a content use <br> 
**Left-margin : auto** <br>
**Right-margin : auto** <br>

**Display :** <br> 
**display: inline** = Displays an element as an inline element (like < span>). <br>
**display: block** = Displays an element as a block element (like < p>). It starts on a new line, and takes up the whole width. <br>
**display: inline-block** = The element itself is formatted as an inline element, but you can apply height and width values. <br>
**display: none** = The element is completely removed. <br>

**Visibility:** <br> 

**Visibility: hidden** = this hides the element. <br>
**Visibility: visible** = it shows the element. <br>

**Border images :** <br>
allows you to specify an image to be used as the border around an element. <br>

**This property requires three pieces of information:**
1- The URL of the image. <br>
2- Where to slice the image. <br>
3- What to do with the straight edges. <br>

**Box-shadow :** <br> 
It allows you to add a drop shadow around a box. <br>
**It comes with these values :** <br> 
- horizontal offset. 
- Vertical offset.
- Blur distance.
- Spread of shadow

**Border radius :** <br> 
It create rounded corners on any box.<br>
------------------------------------------------------------------------------------------ <br> 
**Arrays :** <br> 
A special type of variable. It doesn't just store one value; it stores a list of values. <br>
You create it by giving it a var and the name of the array. <br>
Values of arrays are accessed as if they are a numbered list. <br>
------------------------------------------------------------------------------------------ <br> 
**If else statement :** <br>
**How it works?** <br>
First it checks a condition If resolves to true the first code block is executed, but if it resolves to false the second block is run instead. <br>

**Switch statement :** <br> 
**How it works?** <br>
It starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. <br>

**Loops :** <br>

**For / while / Do while.** <br>

It check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false. <br> 

**Loops counters :** *initialization/ condition/ update.* 