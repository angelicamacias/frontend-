# HTML 
Element: Refers to everyting from the start tag to the end tag and what is between the tags.
```
<p> You are awesome </p>
```
Is an individual component of his email document or web page.  It's a separate component so from the start of the paragraph to the end of the paragraph including any text between.
So the element provides a certain type of functionality and the attribute it enhances that.  
So anything from this tag to the end tag is known as an hasty mail element.

p attribute an hastier male attribute is used to modify the default functionallity 

HTML ATTRIBUTE modifies the default functiionality of an element. They help them achieve certain functions e.g the <a> tag requires the "href" attribute to create a link. 
```
<p><a href -"http://www.cats.com"> Udemy</a></p>       
```
## Creating paragraphs 
we need to use the <p> tag.
<p> This is a paragragh tag </p>
</br> for hava a intro in a paragrphs
Example:

```
<p>Learning a little each day adds up. </br> Research shows that students who make learning a habit are more likely to reach their goals. </p>
```
The result will be:
```
Learning a little each day adds up.
Research shows that students who make learning a habit are more likely to reach their goals. 
```
## HTML HEADINGS
When you see large headlines on the web page they are usually creatd using the heading tags. 
<h1> To <h6>

```
<h1> I have 4 cats </h1>
<h2> I have 4 cats </h2>
<h3> I have 4 cats </h3>
<h4> I have 4 cats </h4>
<h5> I have 4 cats </h5>
<h6> I have 4 cats </h6>
```
This will be:

<h1> To <h6>
<h1> I have 4 cats </h1>
<h2> I have 4 cats </h2>
<h3> I have 4 cats </h3>
<h4> I have 4 cats </h4>
<h5> I have 4 cats </h5>
<h6> I have 4 cats </h6>

## Body 
Only content inside the vody tag is displayed by the webpage

## HTML COMMENTS 
How to create an comments inside your HTML
HTML comments are used to explain the code write.
```
<!-- This is a comment -->
```
## Adding images to a web page
we need the name of the image file 
```
<img srce="images\jellyfish.jpg" alt="Jellyfish Image" width="350" height="350"/>
```
To find the image file type you right click on the image and the type of file is displayed.
alt: what this does is that he lest you specify a text description of the image, so ir for any reason the image is not able to lead may be due to wrong spelling or if he has been located then the text will be displayed instead to see an image of a jellyfish used to be there.

## Add video and audio 
Make sure you use the exact name of the mp3 audio in the text editor or it will not work 

## HTML Lists
We are going to create a list of ordered lists and then ordered 
```
Unorderd List < ul >
```
and
```
Order list < ol >
```

## How to create a simple form 
This form tag has got an opening and closing in, the key that you are creating a form it tells a web browser that you are displaying a form. 
Is used to define from elements contain different types of input.
```
<form></form>
```
The attributes you need to specify the type of input with the type attribute value is read you. 


## Creating a form with a text area

text area = Forms are used to collect data form visitors on a website.

We need to define the form with the form gar and inside the form tag is speciy 
```
<form action=" #" method="post">
        <textarea name="massage" rows="30" cols="50">
        Forms are used to collect data form visitors on a website. 
        </textarea>
        <br><br>
        <input type="submit">
</form>
```
We need to add rules the longer added text area and the more columns you add.

## Creating a form with drop down list options
Sometime you may have fonts that you want user to make his selction from.

we begin with a form tag to indicate you are creating a form and then you have the action attribute which specifies.
Usually you will have a backand server value because when you submit the forms ussaly ther is a backend aserver process that processes the data but because we are not using the server we are submitting. 

The form to itself has of course the hash tag the method we use to do his is pulse
select tag and in the name taf specified in name attribute which is the name i want to call the form selection.
The iption elements define the options you want to select. The list will normally shoe the first item as select and then you can add several more

submit: means if that lifeform will submite whatever data is selected it will submit it to itself because 
our specifier action here because we are not submitted to backend server

## Div; id ; class

Div: Is divistion section in hastier mail documents or page. 
Is used to define a division or sectionin in an HTML document. The <div> tag is used to create a div


The ID: Is used to group block of elements together and form them using csx 

If you use an inside hastier mail document they are players in between a style tag and the style tag is usually plays in the head section of the hastier mail document. 
```
<title> HTML Course </title>
<style>
    div {
        width: 400px:
         background-color:red;
    }
<stayle>
```
id and calas are HTML attribures used as slectors by CSS to target html elements to apply styling to. 
id is unique to a webpage while a class can be used several times within a webpage. 

we can not have two elements on the same page with the same id, they are unique 

the class can be reusable so i can have a class for hast too and use that to style or hinche to tax within the page. 

ID UNIQUE
CLASS IS NOT UNIQUE 

for create the ID, we need to put it inside the start. 

id and class are created and defined inside the starting html tag 
```
<rag id="heading">#
<h2 class="headlines">
```
id is identified with this symbol # an then followed by the name giving the idea (no spaces).


So whetever you five your id when you're styling you need to use that name so that the style knows where to applay the style.
With a dot "." you can idenify a class, followed by the name:
```
.heading{

}
```
So a class is identify with a dot following the name. 

We will give haead in any head to a wedding inside a document where i've specified class to give it that head in to.


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
