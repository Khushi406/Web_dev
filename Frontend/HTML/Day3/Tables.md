# Table in HTML

## Basic Structure
    `<table>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
    </table>`

 Tag	  Purpose
1. <table>	Starts the table
2. <tr>	Table row
3. <th>	Table header cell (bold & centered)
4. <td>	Table data cell

## Attributes to Know
* border
* colspan
* rowspan

## Styling with CSS 
    `table {
    border-collapse: collapse;
    }
    td, th {
    border: 1px solid black;
    padding: 10px;
    }`