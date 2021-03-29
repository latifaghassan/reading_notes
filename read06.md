# Design web pages with CSS Summary

## "LINKS"

**Linking to a specifc part of the same page :**<br>

when you want to add links to the corresponding sections lower down.<br> 
Or you want to add a link from bottom of the page to get you back to the p of the page.<br> 
You can do that by using "id attribute".<br>
You can add it with the < h1 > or < h2 > <br>
The value of the id attribute should start with a letter or an underscore not a number or any other character.<br>
No two id attributes should have the same value. <br>
You write the id attribute on a single page. <br> <br>

Its syntax should be something like that : <br>
< h1 id+"top">element at the top of the page whose id attribute has a value of top< /h1> 
< a href ="#value of id attribute link"><br>

**Linking to a specific part of another page:** <br>

< a href+"link#bottom"><br>

...................................................................................................................................................<br>

## "COLORS"<br>

The color property allows you to specify the color of text inside an element.<br>

**You can specify any color in CSS  in one of three ways :**<br> 

**1\ rgb values :**<br>
These express colors in terms of how much red, green and blue are used to make it up.<br>
**For example:** rgb(100,100,90)<br> 

**2\ hex codes :**<br>
These are six-digit codes that  represent the amount of red,  green and blue in a color, preceded by a pound or hash # sign. <br>
**For example:** #ee3e80<br>

**3\ color names :**<br>
There are 147 predefined color names that are recognized by browsers.<br> 
**For example:** DarkCyan<br>
....................................................................................................................................................<br>
**Background-color :**<br>
You can specify your choice of  background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names.<br>
**For example:**
body { <br>
  background-color:  rgb(200,200,200);}<br>
.....................................................................................................................................................<br>
**Understanding Color:** <br>
Every color on a computer screen is created by mixing amounts of red,  green, and blue. To find the color you want, you can use a color picker.<br>
.....................................................................................................................................................<br>
**HSL Colors :** <br>
**Hue** , it is a degree of a colors wheel. "0 - red , 120 - green , 240 - blue". <br>

**Saturation** , the amount of the gray of the color. "0- chade of the gray, 100% full color".<br>

**Lightness** , lightness of the color. "0% black , 100% white".<br> 
.....................................................................................................................................................<br>
|**Low-contrast** , Text is harder to read when there is low contrast. <br>
**High-contrast** , Text is easier to read when there is higher contrast. <br> 
**Medium-contrast** , reducing the contrast a little bit improves readability. <br>
.....................................................................................................................................................<br>
**Opacity:**<br>
The  transparency of the color.<br>
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity.<br>
**For example:**<br>
p { <br>
background-color: rgba(0,0,0,0.5);}<br>
.....................................................................................................................................................<br>
**HSL & HSLA:**<br> 
You can specify colors as HSL values, with an optional opacity value. It is known as HSLA.<br>
**For example:**<br>
body {<br>
background-color: #C8C8C8;<br>
background-color: hsl(0,0%,78%);}<br>

