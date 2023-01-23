* 
Class 05 - MARKDOWN (page not finished)

*Why use symmantic tags?* *
Symmantic tags are good for screen readers. they are identical to divs and spans and carry with them no difference of how the website looks. 

Although Divs and Spans are different - 
CSS 
**What Is CSS?** - Cascading Style Sheets) allows you to create great-looking web pages.
* *CSS* * is easy to grasp, with braces and rules, you type it in html and then you style it up with CSS.
It is written in cascading style sheets and allows more specifiity to your elements and how they look on the page giving you total control on website design. There are many properties in CSS, you can never learnit all. Although Html is the most commonly used mark up language, there are also other languages used such as svg or xml. 
How can we present these pages?
The document that we have created must be converter to be used on browsers or (User Agents) such as Firefox, CHrome, Brave etc. These user agents present documents we have coded in a visual format, on an aray of devices and screens. 
CSS can be used for styling, this means we can change the colour and size of headings and links. It can be used to create a layout, or for example you can change the layout to suit where you want it on the page, a single column, a triple column. You can also embed animation, or other visuals on the document using CSS. 

CSS Tags:
Div - alt to symmantic html
section and div are no different 
nav ( navigation ) 
it makes your code easier to read. 
inline block - means i will be as wide as the page 
There are some simple and clever ways to change various elements such as adding colour to headings or links. 
Here is the example given in the notes. 
```
H1 {
color: red;
font-size: 5em;
}
```

In this example. The CSS rule opens with a selector. This means that a HTML element has been selected to style. In the example we are styling one of the headings. ```<h1>```
Within the * * Curly Braces* * we have a 'property' and a 'value'. First we specify the colour before a colon, then the value of that property, in this case ```red```after the colon.
* * CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color values. We also have the font-size property. This property can take various size units as a value. * *
```
h1 {
  color: red;
  font-size: 5em;
}
 
p {
  color: black;
}
```
The Language is broken down into Modules. Get used to searching and exploring "mdn css-feature-name". For instance searching for a partiuclar module you could a look at the MDN reference to Background and Borders. 
At this stage, you don't need to worry too much about how CSS is structured; however, it can make it easier to find information if, for example, you are aware that a certain property is likely to be found among other similar things, and is therefore, probably in the same specification.
For a specific example, let's go back to the Backgrounds and Borders module — you might think that it makes logical sense for the background-color and border-color properties to be defined in this module. And you'd be right.
 
**CSS Specifications**
There are specification standard organisations such as W3C , WHATWG, ECMA or Khronos, they publish precisely how each language / technology are supposed to behave.

CSS is developed by a group within the W3C called the CSS working Group. This group is made up of represenetatives of different browser vendors and other people who have interest in CSS. Anything that is developed within CSS is done by the CSS working Group, wether that be for particular browser vendor requests, or if the CSS working group has recongnised features it wants to change. Also anyone using CSS such as web developers are asking for a new feature.
Check implimentation of CSS on web browsers as you may not be able to use this language on all. 
There will be a browser support status shown in every MDN CSS property page, this will be shown within a table named Browser Compatibility. For example to to chech the browser compatibility table for the font family property. 

**Fundamental styling and text**

"Font styles: Properties that affect a text's font, e.g., which font gets applied, its size, and whether it's bold, italic, etc.

Text layout styles: Properties that affect the spacing and other layout features of the text, allowing manipulation of, for example, the space between lines and letters, and how the text is aligned within the content box.

When writing code, rememeber that the text inside an element is affected as one single entitity. you cant select sytle sub sections unless wrapped in an appropraite element. 

for example. 
EXAMPLE HERE
you can write both css and html in the same script
Fonts
To set a font, you use the ```font-family```property.
To set a colour you use the ```color``` property.
```p {
  font-family: serif;
  color: red;
}```


```
body {
background-color: #ffffff);    HEX. 6 digits (highest number is 255 with RGB)
padding: 0;
font-family: "courier new, courier, monospace;
}
header {
background-color: #da517b;
color: #e024de;
height: 300px;
}
h1 {
float: left;
margin-left: 20px;
margin-right: 50px;
color: blue;
text-shadow: 5px 8px 3px white;
}
nav ul {
margin: 0;
padding: 0;
}
nav li {
display: inline-block;
margin: 30px;
margin-right: 20px;
}
nav a{
color: blue;
text-decoration: none;
font-size: 20px;
font-weight: 400;
cursor: pointer;
}
nav a:hover {
color: grey;
text-decoration: underline;
font-size: 22px;
}
main {
width: 800px;
margin: 30px auto;
padding: 10px 20px 30px 50px
}
img {
width: 100%;
}
main p {
font-size: 18px;
background-color: #ffffff;
}
(change html index to small image or big image< img class="small" src=""/>
.small {
width: 50%
}
.center {
margin: 0 auto;
display: block;
```

<h2>TO CHANGE BACK TO GITHUB</h2>
```
git status
git add .
git status
git commit -m "added colours"
git status
git push
```
refresh git hub