 # Domain Modeling 

 BOM: the Browser Object Model something we can refer to inside our JS code in order to change how the something behaves in the browser ex: `windows.innerWidth`BUT when it comes to JS we don't use the BOM when we want to interact with anything inside the browser, instead we use something called DOM: Document Object Model which is par tof the BOM.

 When we have to use DOM to do something inside a website `<script>document.querySelector('#id');</script>` ... documetn.keyword.


inside the DOM we have Nodes, a node is anywhere you have an opeining and closing tags `<header><a>Link here!</a></header>` this is a node. 
and inside of these nodes you gonna have other nodes nested. 

WHY do we need to know this!
When u load a website into the browser u r going to get a node tree gets created as soon as the browser loads the website, in real time when we want to make changes in java script, html and css will be loaded first because the browser creats a DOM when the website is loaded. 

Using JS we can actually allow us to go inside a website and change something constant or make it behave in a different while we are using the website. 


first of all, HOW to grap the node inside the document html!!
the commonly used methods are `getElementByID(); getElementByClassName(), getElementByTagNAme()` 
but the better practice is to use quert selector.


