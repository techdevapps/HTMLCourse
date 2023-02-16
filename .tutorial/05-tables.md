# 📊 HTML Tables
Tables are a powerful way to organize and display data in HTML. In this chapter, we'll explore how to create tables in HTML, including how to define table headers, rows, and cells.

### Creating a Basic Table
To create a basic table in HTML, you'll use the `table` element to define the table, and the tr element to define each row. Within each row, you'll use the td element to define each cell.

Here's an example of a simple table with two rows and two cells in each row:

```html
<!-- Example of a simple table -->
<table>
  <tr>
    <td>🔴 Row 1, Cell 1</td>
    <td>🟢 Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>🟣 Row 2, Cell 1</td>
    <td>🟡 Row 2, Cell 2</td>
  </tr>
</table>
```
In this example, the table element defines the entire table, and each tr element defines a row. Within each row, the td element defines each cell.

Defining Table Headers
In addition to regular cells, you can also define header cells in a table using the th element. Header cells are typically used to define the column or row headers for the table.

Here's an example of a table with header cells:

```html
<!-- Example of a table with header cells -->
<table>
  <tr>
    <th></th>
    <th>🟢 Column 1</th>
    <th>🟣 Column 2</th>
  </tr>
  <tr>
    <th>🔴 Row 1</th>
    <td>🟢 Row 1, Cell 1</td>
    <td>🟣 Row 1, Cell 2</td>
  </tr>
  <tr>
    <th>🟡 Row 2</th>
    <td>🟢 Row 2, Cell 1</td>
    <td>🟣 Row 2, Cell 2</td>
  </tr>
</table>
```
In this example, the first row of the table defines the column headers using the th element. The th element works just like the td element, except that it's used to define header cells.

Merging Cells
Sometimes you may want to merge cells in a table to create a more complex layout. You can do this using the colspan and rowspan attributes on the td and th elements.

For example, here's a table with a merged cell that spans two columns:

```html
<!-- Example of a table with merged cells -->
<table>
  <tr>
    <th></th>
    <th>🟢 Column 1</th>
    <th>🟣 Column 2</th>
  </tr>
  <tr>
    <th>🔴 Row 1</th>
    <td>🟢 Row 1, Cell 1</td>
    <td rowspan="2">🟤 Merged Cells</td>
  </tr>
  <tr>
    <th>🟡 Row 2</th>
    <td>🟢 Row 2, Cell 1</td>
  </tr>
</table>
```
In this example, the second cell in the first row has a rowspan attribute set to 2, which means it will span two rows.

#### Excercise: 
Between `<!--table start-->` and `<!--table end-->` comments create a simple table with at least two rows and two columns. Use appropriate table elements such as table, tr, and td. Give each cell some content, such as text or numbers.

Next, modify the table to include header cells using the th element. Your table should have at least one header row with two header cells.