# Example 27 - Table headings, captions, and accessible structure

## Question

How can a table make row and column relationships clear?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Table headings, captions, and accessible structure</title>
</head>
<body>
  <main>
    <h1>Class schedule</h1>
    <table>
      <caption>Room schedule for Monday</caption>
      <thead>
        <tr><th scope="col">Time</th><th scope="col">Room 1</th><th scope="col">Room 2</th></tr>
      </thead>
      <tbody>
        <tr><th scope="row">9:00</th><td>HTML</td><td>Forms</td></tr>
        <tr><th scope="row">10:00</th><td>Images</td><td>Tables</td></tr>
      </tbody>
    </table>
  </main>
</body>
</html>
~~~

## Expected output

A table appears with a caption, column headings, and a time heading at the start of each row.

## Explanation

The caption names the table. Column and row header cells use th. The scope attribute identifies which data cells each header describes.

## Related lesson

[Read the lesson](../lessons/27-accessible-tables.md)
