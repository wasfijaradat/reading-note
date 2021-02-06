# HTML & CSS
## Introduction + Chapter 1
### **The main goal of a web programmer is to design attractive and usable websites though thus, fo a brgginer it is highly recommended and important to start wiht learning HTML and CSS basically, as these two make up the main two modules of a website which are:**
- *WHAT the content of the website will be, and how it can be structured?*

- *HOW this content would be laid out and  presented to the user.*

***Keywords:***
| Term          | Meaning       |
| ------------- | ------------- |
| Browsers | a software used to access websites by typing a web address  |
| Server   | after asking the browser to open the link, the request will be sent via internet to a special computer called server |


***So, the HTML code perfomrs as the organizer of the webpage, using **elements** and **tags** which act like containers to the elements and the CSS code is responsible to style up this layout to be more attracticve and easy to be explored by users.***

### ***The code example below shows the most basic structure of an HTML file,***
```
<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help
you follow the structure of what is being written.
There may even be sub-sub-headings (or lower-level
headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>
```
The HTML code  is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.
An operning tag `<p>` and a closing tag `</p>` 
the attribute tells us more about the element in the following way e.g `<p lang="hi"> English Paragraph </p>` according to this example; < is an opening angle bracket, > is an closing angle bracket and `<p>` is an opening tag, lang is an attribute name, hi is an attribute value, and `</p>` is a closing tag. 

### ***For any webpage, the HTML file of it divides it into three main parts; head, body and footer.***
- **`<Body>`**: Everything inside this element is shown inside the main browser window.
- **`<head>`** This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a `<title>` element inside the `<head>` element.
- **`<title>`** The contents of the `<title>` element are either shown in the top of the browser, above whereyou usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).


## Chapter 8


## **History of HTML**
Since the web was first created, there have been several different versions of HTML. Each new version was designed to be an improvement on the last (with new elements and attributes added and older code removed). There have also been several versions of each browser used to view web pages, each of which implements new code. Not all web users, however, have the latest browsers installed on their computers, which means that not everyone will be able to view all of the latest features and markup.
Although HTML 4 had some presentational elements to control the appearance of pages, authors are not recommended to use them any more. (Examples include the `<center>` element for centering content on a page, `<font>` for controlling the appearance of text, and `<strike>` to put a line through the text — all of these can be achieved with CSS instead.) In HTML5, web page authors do not need to close all tags, and new elements and attributes will be introduced. At the time of writing, the HTML5 specification had not been completed, but the major browser makers had started to implement many of the new features, and web page authors were rapidly adopting the new markup.
***Keywords:***
| Term          | Meaning       |
| ------------- | ------------- |
| DOCTYPES | a declaration to tell a browser which version of HTML the page is using, for HTML 5 it is ```<!DOCTYPE html>```  |
| COMMENTS   | a text to your code that will not be visible in the browser, you can add the text as follows: ```<!-- comment goes here -->```|
| ID ATTRIBUTE | used to uniquely identify that element from other elements on the page. ```<p id="pullquote">Any thing</p>```|
|CLASS ATTRIBUTE| used to identify several elements as being different from the other elements on the page ```<p class="important">```|
|META DATA| used to supply all kinds of information about your web page. ```<meta>```|
<br>

### WHAT is the difference between BLOCK elements, INLINE elements and DIV element?
- **BLOCK elements** those which always appear to start on a new line in the brwoser window such as; `<h1>, <p>, <ul>, and <li>.`
- **INLINE elements** those will always appear to continue on the same line as their neighbouring elements such as; `<a>, <b>, <em>, and <img>.`
- **DIV element** an element willbe inside the *Block* element, allows you to group a set of elements together in one block-level box. 

## Chapter 17 
### The new HTML5 layout  elements and their uses:

For a long time, web page authors used <div> elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). Authors used class or id attributes to indicate the role of the <div> element in the structure of the page.


![Traditional HTML Layout](https://www.w3schools.com/html/img_sem_elements.gif)

But, New Html 5 Layout Elements is as follows: 



![HTML 5 layout](https://stuyhsdesign.files.wordpress.com/2016/05/yoko-html5.png)

***So, the difference between the two layouts is that the new one (HTML 5 one) is offering clearer and more organized code as it includes more sectioning elements`<div>` elements (containers).*** 

## Chapter 18

### ***The big Question now is, How to understand the audience your site may attract and what information they will expect to find on it? AND How to organize information so that visitors can find what they are looking for?***

*The process of building a new website starts with a simple wire frame to assign the layout of the HTML5 to the contents needed, and then to have a site map describes all the details. But, basically and prior to all of those, we must answer key questions to define our target specifically.*
- WHO is the site for? 
- WHY would people visit my website?
- WHAT my website visitors are looking for and trying to achieve?
- HOW often people will visit the website?

***Wireframe:*** is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

***Now that we know what needs to appear on your site, we can start to organize the information into sections or pages.***

*the diagram below show a simple site map for a photo gallery website*
```mermaid
Home->>Gallery
Home->>About 
Home->> Author's profile
Home->>Contact us
Gallery->>Kids
Gallery->>Nature
Gallery->>Motors
```
***Points to take into consideration while site mapping to help the user communicate, interact, understand, differentiate, and simpligy the informtation in the website easily, it can be done by sectioning, coloring, multi-sizing, styling and so on***
- Content
- Prioritizing
- Organizing
- Visual Hierachy 
- Grouping
- Similarity
<br>
<br>
# JavaScript
## Intro + Chapter 1
## JavaScript can be used in browsers to make websites more interactive interesting, and user-friendly.  
### THINK LIKE COMPUTER TO ACHIEVE YOUR CODE GOAL

***main concepts:***
- JS can make webpages more interactive by Access, Modify, Program, React procedure
- examples of JS interactions with the user such as froms, slide shows, navigation, reload parts of the page , filtering.
- to write a proper script you need to set the goal of your code, structure your website and deign a flowchart or a diagram reflects the process. 

***Rules of Variables:***
- start with a letter or dollar sign or underscore
- it can contain all symbols, letters and nombers except dash or dots 
- don't use reserved words
- variables are case sensitive
- make it descriptive names 
- lowercase the first letter in the first word and upper case the one of the second word

## Terminology:
 ___
 Variables
 ?
temporarily store the bits of information it needs to do its job
 ___
 ___
 DATA TYPES
 ?
 JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.
 ___
 ___
String 
?
The strings data type consists of letters and other characters.
 ____

 ***code example for creating variables***
 ```
 var username;
var message;
username = 'Molly';
message = 'See our upcoming range';
```
## The following Q&A outline will list the main introductory concepts of JS:
- **What is a script?**
a script is a series of instructions that the computer can follow to acieve a goal, scripts usually analogue to cooking recipes, handbooks or manuals.
- **What are the parts of the script to be executed by the browser?**
- it is not necessary that the computer execute the whole script, the browser can use different parts of the script depending on how the user interacts with the webpage. 
 - **How to create a script?**
- to write a good script in JS, start with defining the goal of the script, and list the tasks and steps to achieve that goal, and build a flow chart presents the orders sequence in your script.
- **How do computers fit in with the world around them?**
computers create models of the world using data, because computers are'nt able to realize models or things in real, programmers use data presented to computers as sort of instructions to get them undertand the model or the thing intended by instructions (Logic, numeriacl, strings) using specific syntax rules to describe those physical things by their properties, events and methods. 
- **How browsers see a webpage?**
it will recieve a page as HTML code, then creat a model of the page and store it in the memory, and finally ise a rendering engine to show the webpage on screen. this rendering enginer of (translator) will be the JavaScript code. 
- **How can we write a script for a webpage?**
HTML code, CSS code and JavaScript code will all fit together to render a the webpage designated. the HTML is for the contents layer, CSS is for the presentation layer, and JS code for behavior or interaction layer. this comination process between those three codes is PROGRESSIVE ENHANCEMENT.

