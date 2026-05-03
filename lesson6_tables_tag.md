# HTML Tables

## 1. Define an HTML Table
An HTML table is used to display data in rows and columns.

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

---

## 2. Table Structure

### Table Rows (`<tr>`)
Defines a row in a table.

```html
<tr>
    <td>Row Data</td>
</tr>
```

### Table Cells (`<td>`)
Defines data cells.

```html
<td>John</td>
```

### Table Headers (`<th>`)
Defines header cells.

```html
<th>Name</th>
```

---

## 3. HTML Table Tags

- `<table>`: Defines a table  
- `<tr>`: Defines a row  
- `<td>`: Defines a data cell  
- `<th>`: Defines a header cell  
- `<caption>`: Defines a table caption  
- `<colgroup>`: Groups columns for formatting  
- `<col>`: Defines column properties  
- `<thead>`: Groups header content  
- `<tbody>`: Groups body content  
- `<tfoot>`: Groups footer content  

---

## 4. Table Borders

```html
<style>
table, th, td {
    border: 1px solid black;
}
</style>
```

---

## 5. Collapsed Borders

```html
<style>
table {
    border-collapse: collapse;
}
</style>
```

---

## 6. Table Sizes

```html
<table style="width:100%">
<td style="width:50%">
```

---

## 7. Row Height

```html
<tr style="height:50px">
```

---

## 8. Table Headers

### Horizontal
```html
<th>Name</th>
<th>Age</th>
```

### Vertical
```html
<tr>
    <th>Name</th>
    <td>John</td>
</tr>
```

---

## 9. Caption

```html
<caption>Employee Table</caption>
```

---

## 10. Colspan & Rowspan

### Colspan
```html
<td colspan="2">Merged Columns</td>
```

### Rowspan
```html
<td rowspan="2">Merged Rows</td>
```

---

## 11. Complete Example

```html
<!DOCTYPE html>
<html>
<head>
<style>
table {
    border-collapse: collapse;
    width: 100%;
}
th, td {
    border: 1px solid black;
    padding: 8px;
}
</style>
</head>
<body>

<table>
    <caption>Student Scores</caption>

    <thead>
        <tr>
            <th>Name</th>
            <th colspan="2">Subjects</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td rowspan="2">John</td>
            <td>Math</td>
            <td>90</td>
        </tr>
        <tr>
            <td>Science</td>
            <td>85</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td colspan="3">End of Report</td>
        </tr>
    </tfoot>

</table>

</body>
</html>
```
