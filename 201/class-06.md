# Chapter 3: “Object Literals” (pp.100-105)

## JavaScript is an object-based language. Everything is an object in JavaScript.
## There are 3 ways to create objects.
1. By object literal
*example* The syntax of creating object using object literal `object={property1:value1,property2:value2.....propertyN:valueN}  `
2. By creating instance of Object directly 
*example* The syntax of creating object directly `var objectname=new Object();  `
3. By using an object constructor 
*example* The syntax of creating object using an object constructor `e=new emp(103,"Whatever",30000);  ` 

# Chapter 5: “Document Object Model” (pp.183-242)

## What is the DOM? 
*The Document Object Model (DOM) is a programming interface for HTML documents. It represents the page so that browsers can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.*

## DOM & JS
*The DOM was designed to be independent of any particular programming language, making the structural representation of the document available from a single, consistent API. API = DOM + JavaScript*

## Accessing the DOM
*ifferent browsers have different implementations of the DOM, and these implementations exhibit varying degrees of conformance to the actual DOM standard, but every web browser uses some document object model to make web pages accessible via JavaScript.*

## Keywords:

| Term      | Description |
| ----------- | ----------- |
|   Document| When a member returns an object of type document, his object is the root document object itself.|
|    Node    | Every object located within a document is a node of some kind. In an HTML document, an object can be an element node   |
|    Element  | The element type is based on node. It refers to an element or a node of type element returned by a member of the DOM |
|NodeList|A nodeList is an array of elements, like the kind that is returned by the method document.querySelectorAll()|

