# Example 26 - HTML tables: rows, columns, and cells

## Question

How can you represent data in rows and columns?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>HTML tables: rows, columns, and cells</title>
</head>
<body>
  <main>
    <h1>Weekly harvest</h1>
    <table>
      <caption>Vegetables collected this week</caption>
      <thead>
        <tr><th scope="col">Vegetable</th><th scope="col">Count</th></tr>
      </thead>
      <tbody>
        <tr><td>Tomatoes</td><td>8</td></tr>
        <tr><td>Cucumbers</td><td>3</td></tr>
      </tbody>
    </table>
  </main>
</body>
</html>
~~~

## Expected output

A captioned table appears with two column headings and two rows of harvest data.

## Explanation

table represents tabular data. tr creates rows, th creates header cells, and td creates data cells. Use tables for relationships between data, not for page layout.

## Related lesson

[Read the lesson](../lessons/26-html-tables.md)
