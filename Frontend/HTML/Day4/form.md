# Form
  - - A form is a container that collects user input and sends it to a server for processing — like signing up, logging in, searching, or posting a comment.

## Basic Form Structure
    `<form action="/submit" method="POST">
    <!-- form elements go here -->
    </form>`
* action: where the form data goes (usually a server)
* method: usually GET or POST
  
### Essential Form Attributes
Attribute	Description
1. action	:    URL where the form data should be sent
2. method :   	HTTP method (GET or POST)
3. target	:Where to display the response (_self, _blank, etc.)
4. autocomplete:	Enables/disables browser autofill
5. novalidate:	Disables built-in HTML5 validation

##  Important Form Elements

Tag	        Use
1. `<input>`	Single-line input (text, email, password, etc.)
2. `<label>`	Describes input field
3. `<textarea>`	Multi-line input (like message box)
4. `<select>`	Dropdown menu
5. `<option>`	Options inside `<select>`
6. `<button>`	Button (usually to submit the form)

## Common Input Types
1.` <input type="text">  `      <!-- Text field -->
2. `<input type="email">`       <!-- Email field -->
3. `<input type="password">`    <!-- Password field -->
4. `<input type="number"> `     <!-- Number input -->
5. `<input type="checkbox">`    <!-- Checkbox -->
6. `<input type="radio">`       <!-- Radio buttons -->
7. `<input type="submit">`      <!-- Submit button -->

##  Form Input Elements

1. Text Inputs
  `<label for="name">Name:</label>
<input type="text" id="name" name="username" required>`
Attribute       	Meaning
1. type="text"   	Regular single-line input
2. name         	Key used to send data
3. id           	Connects input with <label>
4. required	      Makes field mandatory
5.placeholder    	Hint shown in the input

1. Password, Email, Number
   `<input type="email" name="email">
<input type="password" name="pass">
<input type="number" name="age" min="1" max="100">`

2. TextArea (Multiline Input)
`<label for="msg">Message:</label>`
`<textarea id="msg" name="message" rows="4" cols="30"></textarea>`

3. Checkboxes
   `<label><input type="checkbox" name="skills" value="HTML"> HTML</label>
<label><input type="checkbox" name="skills" value="CSS"> CSS</label>`

4. Radio Buttons
   `<label><input type="radio" name="gender" value="male"> Male</label>
<label><input type="radio" name="gender" value="female"> Female</label>`

5. Dropdown (Select Box)
   `<select name="country" required>`
  `<option value="">--Select Country--</option>
 ` <option value="india">India</option>
  `<option value="usa">USA</option>
`</select>`

6. Buttons
   *  Submit Button  : `<button type="submit">Submit</button>`
   *  Reset Button   : `<button type="reset">Reset</button>`
   *  Custom Button  : `<button type="button" onclick="alert('Hello')">Click Me</button>`

## Validation Attributes

Attribute	        Purpose
1. required     	Field must be filled
2. min, max     	Min/max for number/date
3. maxlength    	Max characters allowed
4. pattern	      Regex for custom validation
5. readonly	      Prevents editing
6. disabled	      Grays out the field

* Grouping Fields: `<fieldset>` and `<legend>`
`<fieldset>`
`  <legend>Personal Info</legend>`
  `<input type="text" name="fname" placeholder="First Name">`
`</fieldset>`
*  Hidden Inputs
  `<input type="hidden" name="userid" value="12345">`



#  What is `<fieldset>` in HTML?
`<fieldset>` is a semantic container that groups related elements in a form, typically inputs, checkboxes, radio buttons, etc.
It is often used for visual grouping and to improve accessibility for screen readers.

#  What is `<legend>` in HTML?
`<legend>` is used inside a `<fieldset>` and serves as the title or label for that group of form elements. It's like a heading for the section.

`<fieldset>`
  `<legend>Personal Information</legend>`
  
  `<label for="name">Name:</label>`
  `<input type="text" id="name" name="name">`

  `<label for="email">Email:</label>`
  `<input type="email" id="email" name="email">`
`</fieldset>`