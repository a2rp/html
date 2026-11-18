# Example 35 - Form submission: name, method, action, and enctype

## Question

Which form attributes describe where and how data is submitted?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Form submission: name, method, action, and enctype</title>
</head>
<body>
  <main>
    <h1>Search the garden guide</h1>
    <form action="/search" method="get">
      <label for="query">Search terms</label>
      <input id="query" name="q" type="search">
      <button type="submit">Search</button>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

A search field and button appear. Submitting sends the named value to the /search path using the GET method. A site needs a handler at that path to show results.

## Explanation

action names the destination, method selects how the browser sends the form, and name identifies each submitted value. This example is a form structure and does not include a server.

## Related lesson

[Read the lesson](../lessons/35-form-submission.md)
