# What is CSS?
-- CSS is like clothes for your webpage.  
Your HTML is the skeleton (plain), and CSS is how you dress it up — colors, spacing, layouts, fonts, animations, everything.

### 1. Selectors - Choosing What to Style  
   **HTML Code**: `<p>I am a paragraph.</p>`  
   `<div id="box"></div>`  
   `<h1 class="title">Welcome</h1>`  
    **CSS Code**: `p {color: red;}`  
   `#box { background-color: yellow; }`  
`.title {
  font-size: 40px;
}`
  * p = all paragraphs  
  * #box = one unique box (ID = like a name tag)
  * .title = any element with class "title" (class = label group)

### 2. Colors
 ` color: red;`     /* name */
`color: #ff0000; `             /* hex code */
`color: rgb(255, 0, 0);  `     /* RGB */


### 3. Fonts – Changing the Letters
  **CSS** : `Fonts – Changing the Letters`  
  `font-family: Arial, sans-serif;`   
  `font-weight: bold;` 
   `font-style: italic;`


### 4. Units

You can size things using units.

Unit	Means	Like...
px	pixels (fixed size)	📏 "20px" = exactly 20 dots
%	percentage of parent size	🧩 50% = half of parent width
em	based on parent font-size	🧁 "2em" = 2× parent text size
rem	based on root font-size	🌍 consistent across site
vh	1% of screen height	📱 screen-based layout control
vw	1% of screen width	📐 use for responsive widths

