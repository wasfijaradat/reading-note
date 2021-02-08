# Duckett HTML
## Chapter 3 pge 62 - 73
*There are three main types of listing in HTML:
1. ordered list using numbering`<ol>   </ol>`
1. unordered list using bullets  `<ul>  </ul>`
1. definition list used to define terminology `<dl>  </dl>`
 
 ***example***

 ```
 <ul>
<li>Mousses</li>
<li>Pastries
<ul>
<li>Croissant</li> //nested listing "sublisting" 
<li>Mille-feuille</li> // nested listing "sublisting" 
<li>Palmier</li> //nested listing "sublisting" 
<li>Profiterole</li> //nested listing  "sublisting" 
</ul>
</li>
<li>Tarts</li>
</ul>
}
```

## Cahpter 13 300 -329
***Main outlines in CSS styling:***
1. CSS can affect the appearance of boxes width, height, limitng width and height `min-width` , `max-width` , `min-height` , `max-height`
1. More advanced properties to controm the box appearance are properties such as `Border`, `Margin`, `Padding`, `white-space` `vertical-margin` `margin`, `border-width`, `border-style` , `border-color` , `text-align` , `display` , `visibility` , `box-shadows` ,`border-radius` 

# Duckett JS

## Chapter 2 pge 70 - 73

*array literal:* create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The
values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
***example***

```
var colors
c02/ js/array-constructor.js
new Array('white ' ,
'black',
'custom ' );
var el = document.getElementByid( ' co lors ' );
el.innerHTML = colors.item(O);
```
if we need to update the value of the second index in the array (black) to (beige), can be done by `colors[2] = 'beige ' ;`


## Chapter 4 pge 162 - 182

***you can see that an `if ... e 1 se` statement al lows you to provide two sets of code:***
1. one set if the condition evaluates to true
2. another set if the condition is false

*example*
```
if (score >= 50){
    alert('congratulate);
}
else {
    alert('hard luck');
}
```

3. Switch statement is declaring a varibale for many cases and finally a default case, the code runs each statement from top to bottom if one matches the variable otherwise go to the default case. 

*example*

```
var msg;
var level = 2;
II Message
11 Level
c04/js/switch-statement .js
/I Determine message based on level
switch (level) {
case 1:
msg = 'Good luck on the first test ' ;
break;
case 2:
msg = 'Second of three - keep going!';
break;
case 3:
msg = ' Final round, almost there!';
break;
default :
msg = 'Good l uck!';
break;
var el = document.getEl ementByld('answer ' );
el .textContent = msg;
```
4. loops are to check a condition, if its true a code block will keep running till the condition get false. 
loops can be coded using for, While, and Do while.
***every loop needs a counter for iterations otherwise the code will keep running infinitely (error) if the condition will keep being true.***

