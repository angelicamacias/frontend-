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
