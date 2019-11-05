# Tables in HTML
There are 4 parts to adding tables into your HTML...
- Table tag 
    - This is how you add the table itself, although its no table until there are rows and data.
- Table Header
    - within the first row your data tag inserted will be a `<th>` this is for the top row so you can have headers for each column.
- Table Row
    - each row will be kept inside one `<tr>` tag (all except the forst row, which will be inside a table header tag...)
- Table data
    - the smallest unit in the table is the individual table data `<td>` tag, this is for each individual cell within the table.



    <table>
    <tr>
    <th></th>
    <th>1st column header</th>
    <th>2nd column header</th>
    <th>3rd column header</th>
    </tr>

    <tr>
    <th>1st row header</th>
    <td>1x 1y</td>
    <td>2x 1y</td>
    <td>3x 1y</td>
    </tr>
    
    <tr>
    <th>2nd row header</th>
    <td>1x 2y</td>
    <td>2x 2y</td>
    <td>3x 2y</td>
    </tr>
    
    <tr>
    <th>3rd row header</th>
    <td>1x 3y</td>
    <td>2x 3y</td>
    <td>3x 3y</td>
    </tr>
    
    </table> 

    ## Here is the HTML for that table.

    `<table>`

    `<tr>`
    
    `<th></th>`
    
    `<th>1st column header</th>`
    
    `<th>2nd column header</th>`
    
    `<th>3rd column header</th>`
    
    `</tr>`

    
    `<tr>`
    
    `<th>1st row header</th>`
    
    `<td>1x 1y</td>`
    
    `<td>2x 1y</td>`
    
    `<td>3x 1y</td>`
    
    `</tr>`
    
    `<tr>`
    
    `<th>2nd row header</th>`
    
    `<td>1x 2y</td>`
    
    `<td>2x 2y</td>`
    
    `<td>3x 2y</td>`
    
    `</tr>`
    
    `<tr>`
    
    `<th>3rd row header</th>`
    
    `<td>1x 3y</td>`
    
    `<td>2x 3y</td>`
    
    `<td>3x 3y</td>`
    
    `</tr>`
    
    `</table>`