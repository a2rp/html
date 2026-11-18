# Example 44 - Dialog elements

## Question

How can an open dialog be represented in HTML without running a script?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Dialog elements</title>
</head>
<body>
  <main>
    <h1>Garden notice</h1>
    <dialog open aria-labelledby="notice-title">
      <h2 id="notice-title">Watering notice</h2>
      <p>Please water the shared plants before noon.</p>
    </dialog>
  </main>
</body>
</html>
~~~

## Expected output

The page displays an open dialog with a heading and a notice. It is open but is not modal because no script called showModal().

## Explanation

dialog represents a dialog box. The open attribute makes it visible in the page. A modal dialog requires a call to the dialog's showModal method, which is outside this HTML-only example.

## Related lesson

[Read the lesson](../lessons/44-dialog-element.md)
