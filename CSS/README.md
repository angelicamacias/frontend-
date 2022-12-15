=====================================================
## CSS Syntax rule

p { color :red; font-size:24px }

color :red; ==> declaration block 
color: property
red: value

font-size:24px ==> declaration block
font:property
value:24px

CSS is used to style HTML elements. 
p: They slect all the HTML element you want to applay styling to in this illustration. These elect is the P tag which is used to create paragraphs in his team out there declare it on block. 
property: refers to what style you want to apply to the HTML selector and the value is the outcome 

The declaration block are nclosed inside curly braces. 
```
{ color :red; font-size:24px };
```

We need to put a ";" in the end of each declaration block, and the ":" is used to separate the property value.

## CSS ID selector #

#---> This is used to apply styling to a unique HTML element on a webpage.  
ID slector is used to apply stying to a unique HTML element.
Ther can only be one named id selecotr per webpage. 

It means select is unique, we can't have two id name the on the same web page 

So we define the ID for each paraghat 

## CSS CLASS SELECTOR  .
The class selector is an attribute that is specified in the opeing tag of HTML element. 
Class selector can be used to apiply styling to several HTML elements on the same webpage. 

IT uses the period or dot as a sumbol(.)

CLASS SELECTOR ----> .
```
<p class='para1">
</p>
```
the value of the attribute is the name of the claas which is power at 1 
Wherever you define the class you can be use it several time on the same web page.
The class is reusable 

## CSS Group selectors

```
 h1, h2, h3 {
                    font-family: Georgia, Arial;
                    text-align:center;
                    color: #0F230F;


    }

    h1{ font-size: 1.7cm; }
    h2{ font-size: 1.5cm; }
```

Group selectors are used to apply identical styling to a group of elements. 

if i want three tags with the similar or idential stylee then we can gruped them together. 

we need to specify the first one and then you separate them by ","= h1, h2, h3:
```
h1, h2, h3 {
                    font-family: Georgia, Arial;
                    text-align:center;
                    color: #0F230F;


    
```
So for give style for each hech we do: 
```
h1{ font-size: 1.7cm; }
h2{ font-size: 1.5cm; }
```
specifity or ecah hech the style that we want. 

## CSS Color property 

We can specify a column by column names or we could use:
- the hex decimal values. 
```
color: #0F230F;
```
-Color name 
- RGB Red Green Blue colors
- HSL colros(hue, saturation)

We are going to use a hex value to chang the color of the text 

## Font-Family property 
Good practice to specify more than one value for the font -family property 
Font familu is used to set the font type of a text. 
We are going to use the font property to set the font for the text.  
we will incluing another 
```
.para1  {
        
                color:#2E3DEA;
                font-size:32px;
                font-family:Arial, Georgia, "Times New Roman";
        
        }
```
When we are specigying the font family we need to specify a few fonts and the others will act as a backup.
When used in the font family always specify more than one font type of the value. 

## CSS Font - Weight property 
Font-wight property is used to specify of define the boldness and thickness of a font (text)

Font -weight vales you can use include:
Normal (Defalut value or 400)
Bold (or 700)
Numeric value (100-900) thin -> thick 

## Backgrounf -color property 
```
background-color :#fff;
```
background-color property is used to set of change the background color of an HTML element.
#color picker tool: This tol makes it easy to crate, adjust and experiment with cosumt color for the web. 
```
body{
    background-color:#C052F3;
}
```
## Coments
Comments are usfuel in that they help describe the code, they can also be use the troubleshooting mechanism. 

CCS comments are used to describe and test css code 

```
/* This is a comment */
```
comments are ignored by the web browser.
This syntax only works into the CCS 

## Margin - Property 

Margin property is used to create space around an HTML element. 
Margin does not have a background color.
It's completely transparent. 
The margin is applied in order off top right bottom left top right bottom 
The order in which the margin is applied:
 - Top 
 - Right
 - Botttom
 - Left 
= T.R.B.L. ==== TROBL
 - margin-Top 
 - margin-Right
 - margin-Botttom
 - margin-Lef

---> When we see the word magin we are talking about all four corners.

 margin:auto; broeser has set reset the margin space around. 

if you want to specify the margin ina shorthand way like:

```
margin:20px 30px;
```
margin:auto;
margin: 20px 30px;    (20 px is applied to top and bottom margi and 30px right and left)
margin: 18px 23px 35px;  (top, right and bottom)
margin: 38px; (the same value for T.R.B.L)

## css padding - property 
Pradding property is used to create space between an HTML element and the border that surrounds it. 
When applying padding it usually is applied in the order:
 -top 
 -right 
 -bottom 
 -left. 
But we can also be specific on target specific section of the element
 -padding: top 
 -padding: right 
 -padding: bottom 
 -padding: left

Is we use just the word "padding" as the property you what you are specifiying to apply padding to the top, right, bottom and left, 
padding: 20px 30px; (20 px is applied to top and bottom padding and 30px to right and left padding)---> the padding incress inside the element. 
padding: 18px 23px 35px; (top, right and left, and bottom)
padding: 38px;
20 px is applied to top and bottom padding

## CSS Border -Radios property 

Border - Radios property is used to create runded corners. 
```
 border-radius:30px;
 ```
 ## Font - Size property 

 Font-size property 
 Is used to change or ser the size of a text, the defualt browser size setting is 16px

 We have two methods

 Sets the size of a text for an html element: Absolute and relative 

 abolsut: pixel unit or measurement e.g 16px;

 relative: m value, m equal to the value of the defualt peaks of value. eg: em unit of measurement 1em = 16 px;

Absolute using pixel is a static balue and not as felxible for accessibillty user comprend to using em values which ar relative and felxible. 

We can seta percentage value relative to the peaks of value: 

%value
ef 62.5% of defult 16px = 10px
em value will be based on 10 px
10px then becomes 1em 

## CSS Line -Height property 

Line - height property is used to create space bewteen each line of text in a  paragagh 


## Text decoration 

Text decoration property is used to set or remove declarations form a text the desecration property.
This is used to add or remove decorations from a text. 
By defalut when we create a link the text on the link has an on the line

underline(default) places underline on the text
Line-thorugh( puts a line through the text)
Overline(places line above text)


## Align Property 

text-align property is used to set the alignment of text on a webpage. 
=====================================================


