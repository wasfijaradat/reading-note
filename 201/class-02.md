# Duckett HTML

## Chapter-2
***To design an elementary HTML webpage starting witht he HTML file to include the contents of your webpage, Home one basically, this content can be presented in the webpage using two markup types (tags):***

1. structural markup: such as headings `<h1> </h1>`, paragraphs `<p></p>`, bold `<b>`, italic `<i>` ,superscript `<sup>` , subscript `<sub>`, breaks `<br />`, 
1. semantic markup: to emphasize an intended text such as `<strong>` `<em>`, Quotations `<q>`,  Abbreviations `<abbr>`,  citation `<cite>`, definitions `<dfn>`, author details `<address>`

## Cahpter-10
***continuing on the three elementary files to have a good looking, contentful, and interacing website; the second element is CSS syntax to style up the HTML document*** *this styling can be inline, embeded, or external*
### CSS selectors

|Selector name|function|symbol|
|-------------|--------|------|
|Universal Selector|targets all elements in the HTML file|*{}|
|Type Selector|targets the tag container|h1, h2 {}|
|Class Selector|targets the class attribute of specfic value|.note{}|
|id Selector|targets the element whose id attribute has a specific value|#intro{}|
|child Selector|targets element that are children of other elements|li>a{}|
|Descendant Selector|Targets any `<a>` elements that sit inside an element, even if there are other elements nested between them|p a{}|
|Adjacent Sibling Selector|targets the first element after any an assigned element|h1 + p {}|
|General Sibling Selector|targets both sibling elements|h1~p{}|

***If there are two or more rules that apply to the same element, it is important to understand which will take precedence.***
* If the two selectors are identical, the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.
* If one selector is more specific than the others, the more specific rule will take precedence over more general ones. 

***example of selectors priority*** 

HTML code

`<h1>Potatoes</h1>`
`<p id="intro">There are <i>dozens</i> of different`
`<b>potato</b> varieties.</p>`
`<p>They are usually described as early, second early`
`and maincrop potatoes.</p>`

CSS code

`* {`
`font-family: Arial, Verdana, sans-serif;}`
`h1 {`
`font-family: "Courier New", monospace;}`
`i {`
`color: green;}`
`i {`
`color: red;}`
`b {`
`color: pink;}`
`p b {`
`color: blue !important;}`
`p b {`
`color: violet;}`
`p#intro {`
`font-size: 100%;}`
`p {`
`font-size: 75%;}`

Result 
![Result](imges/result.png);

***Why use External Style Sheets?***
1. All of your web pages can share the same style sheet.
1. the same code does not need to be repeated in every page (which results in less code and smaller HTML pages).
1. The HTML code will be easier to read and edit because it does not have lots of CSS rules in the same document.


# Duckett JS
## Chapter-2
**Variable Declaration (assigning a value for a variable)**
*example* `var quantity = 40`
### var: to inform the interpreter that we're creating a variable
- quantity: is the varibale name
- 40: is the variable value
### Important: **variables can be used to store all data types; string, numerical, and boolean**


**Rules of Variables:**

- start with a letter or dollar sign or underscore
- it can contain all symbols, letters and nombers except dash or dots 
- don't use reserved words
- variables are case sensitive
- make it descriptive names 
- lowercase the first letter in the first word and upper case the one of the second word


**main concepts**

1. Variables are used to temporarily store pieces of information used in the script.
1. Arrays are special types of variables that store more than one piece of related information. e.g. `var colors; colors ['white', 'black', ' custom '];`

# Comparison and Logical operators

___
**==**
 ?
compares two valuse regardless of their data types to check if they are same 
 ___
 
 ___
 **!=**
 ?
check if the two values are NOT the same 
 ___
 
 ___
**===**
?
stricktly equal caheck if the two values are identical in their shape and value 
 ____
 **!==**
?
stricktly NOT equal caheck if the two values are NOT identical in their shape and value 

 ____
  **>, <, >=, <=**
?
 compare two integers, comparison ops result is either TRUE or FALSE
 ____

  **& , ||,  !**
?
logical op AND, OR, NOT respectively, allows us to compare results of multiple comparison operations
 ____

  **Loops**
?
For, While, do while ops sounds like the if statement in its structure and operation, if a cond satisfies true then go inside a loop of commands to execute them, till the cond get to be false then stop repeating the code
 ____


