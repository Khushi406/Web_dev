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
action	URL where the form data should be sent
method	HTTP method (GET or POST)
target	Where to display the response (_self, _blank, etc.)
autocomplete	Enables/disables browser autofill
novalidate	Disables built-in HTML5 validation

##  Important Form Elements

Tag	        Use
1. <input>	Single-line input (text, email, password, etc.)
2. <label>	Describes input field
3. <textarea>	Multi-line input (like message box)
4. <select>	Dropdown menu
5. <option>	Options inside <select>
6. <button>	Button (usually to submit the form)

## Common Input Types
1. <input type="text">        <!-- Text field -->
2. <input type="email">       <!-- Email field -->
3. <input type="password">    <!-- Password field -->
4. <input type="number">      <!-- Number input -->
5. <input type="checkbox">    <!-- Checkbox -->
6. <input type="radio">       <!-- Radio buttons -->
7. <input type="submit">      <!-- Submit button -->

