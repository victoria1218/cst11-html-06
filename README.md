# Tables, Blocks and Dynamic Changes

We will be introducting 3 topics today, but not looking at each of them in much detail:
* tables
* display blocks
* dynamic changes to styles

# Tables
Tables used to be used quite a lot for organizing web pages, but this has fallen out of favor since the inception of Styles for layouts.  Tables are still great for organizing data, and we can style them as well.

Tables are still very useful for planning out content in grid shapes, because many layouts still depend on them.

We always start with a table that is a complete grid with rows and columns.
```<tr> </tr>```
tr tags are used to define the rows.
```<td> </td>```
td tags are nested inside the rows to define the columns.

Then, we can use the colspan and rowspan attributes to make a row or column extend beyond its own cell into neighboring cells. Note that doing so removes some of the cells in that row/column.




Open the file tables.html and look at the content.
This is a pretty boring table, with no additions.  However, we are going to add a whole lot of styles all at once.
Add the following text into your <head></head>
```
 <link rel="stylesheet" href="tablestyle.css">
 ```
 This adds an external document into your html.  It is a way of importing your styles from another file.  Open up tablestyle.css and see what it looks like.

 ## Assignment
 Create each of the tables that has been defined in the document ***tableassignment.pdf***
 
