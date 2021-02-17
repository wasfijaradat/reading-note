# “FORMS , LISTS & TABLES ”

## The `<form>` Element
*The HTML `<form>` element is used to create an HTML form for user input:*

```
<form>
.
form elements
.
</form>
```

## The `<input>` Element
*The HTML `<input>` element is the most used form element.*

*An `<input>` element can be displayed in many ways, depending on the type attribute.*

*Here are some examples:*

| Piece of code     | Description |
| ----------- | ----------- |
|  `<input type="text">`| Displays a single-line text input field|
|  `<input type="radio">` | Displays a radio button (for selecting one of many choices)  |
|  `<input type="checkbox">`| Displays a checkbox (for selecting zero or more of many choices)|
|`<input type="submit">`|Displays a submit button (for submitting the form)|
|`<input type="button">`|Displays a clickable button|

## HTML Input Types
***Here are the different input types you can use in HTML:***

* `<input type="button">`
* `<input type="checkbox">`
* `<input type="color">`
* `<input type="date">`
* `<input type="datetime-local">`
* `<input type="email">`
* `<input type="file">`
* `<input type="hidden">`
* `<input type="image">`
* `<input type="month">`
* `<input type="number">`
* `<input type="password">`
* `<input type="radio">`
* `<input type="range">`
* `<input type="reset">`
* `<input type="search">`
* `<input type="submit">`
* `<input type="tel">`
* `<input type="text">`
* `<input type="time">`
* `<input type="url">`
* `<input type="week">`

## The <label> Element

Notice the use of the element in the example above.

The tag defines a label for many form elements. The element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element. The element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes)

*  ***because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox. The for attribute of the tag should be equal to the id attribute of the element to bind them together.***

## Radio Buttons
**The `<input type="radio">` defines a radio button.**

*Radio buttons let a user select ONE of a limited number of choices.*

*Example: A form with radio buttons:*

```
<form>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>
  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>
</form>
```

## Checkboxes
**The `<input type="checkbox">` defines a checkbox.**

*Checkboxes let a user select ZERO or MORE options of a limited number of choices.*

*Example: A form with checkboxes:*

```
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

## The Submit Button

**The `<input type="submit">` defines a button for submitting the form data to a form-handler.**

The form-handler is typically a file on the server with a script for processing input data. The form-handler is specified in the form's action attribute.

*Example: A form with a submit button:*

```
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

## The `<textarea>` Element 
**The  `<textarea>` element defines a multi-line input field (a text area):**
*Example*

```
<textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>
```

## Input Type Password
`<input type="password">` **defines a password field:**

*Example*

```
<form>
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username"><br>
  <label for="pwd">Password:</label><br>
  <input type="password" id="pwd" name="pwd">
</form>
```

## Input Type Email
**The `<input type="email">` is used for input fields that should contain an e-mail address.**
Depending on browser support, the e-mail address can be automatically validated when submitted. Some smartphones recognize the email type, and add ".com" to the keyboard to match email input.

*Example*

```
<form>
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email">
</form>
```

## Input Type Url
**The `<input type="url">` is used for input fields that should contain a URL address.**
Depending on browser support, the url field can be automatically validated when submitted. Some smartphones recognize the url type, and adds ".com" to the keyboard to match url input.

*Example*

```
<form>
  <label for="homepage">Add your homepage:</label>
  <input type="url" id="homepage" name="homepage">
</form>
```
