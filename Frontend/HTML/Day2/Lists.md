# Lists in HTML

## Unordered List (<ul>)
- Used when the order doesn’t matter (e.g., shopping list, features list).
  `<ul>
     <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
   </ul>`

## Ordered List (<ol>)
- Used when the order does matter (e.g., steps to install software, rankings).
    `<ol>
        <li>Wake up</li>
        <li>Brush teeth</li>
        <li>Start coding</li>
    </ol>`


## Nested Lists    
- Lists inside a list item.
    `<ol>
    <li>Frontend
        <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JS</li>
        </ul>
    </li>
    <li>Backend</li>
    </ol>` 


## Type Attribute
- Customize the style of the list.
    `<ol type="A">
    <li>First</li>
    <li>Second</li>
    </ol>`
* For <ol>: type="1", "A", "a", "I", "i"
* For <ul>: type="circle", "square", "disc"
 Note: type is deprecated in HTML5 for <ul>, so avoid it unless you're styling with CSS.


 # Quetions :
 1. What’s the difference between <ul> and <ol>?
 2. What tag is used for list items?
 3. Can lists be nested? How?
 4. How do you change list numbering to alphabets?
 5. Which tag is used for unordered lists with square bullets?
