# Example 18 - Unordered, ordered, and description lists

## Question

How can HTML show items, steps, and term-description pairs?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Unordered, ordered, and description lists</title>
</head>
<body>
  <main>
    <h1>Garden tasks</h1>
    <h2>Supplies</h2>
    <ul>
      <li>Seeds</li>
      <li>Soil</li>
    </ul>
    <h2>Planting steps</h2>
    <ol>
      <li>Fill the pot with soil.</li>
      <li>Plant the seed.</li>
    </ol>
    <dl>
      <dt>Compost</dt>
      <dd>Decomposed organic material used to improve soil.</dd>
    </dl>
  </main>
</body>
</html>
~~~

## Expected output

The browser shows a bulleted supply list, a numbered set of steps, and a term followed by its description.

## Explanation

Use ul when order does not matter, ol when sequence matters, and dl for groups of terms and descriptions.

## Related lesson

[Read the lesson](../lessons/18-lists.md)
