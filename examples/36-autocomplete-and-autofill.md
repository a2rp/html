# Example 36 - Autocomplete and autofill

## Question

How can autocomplete hints help browsers fill familiar fields?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Autocomplete and autofill</title>
</head>
<body>
  <main>
    <h1>Contact details</h1>
    <form>
      <p><label for="name">Full name</label>
        <input id="name" name="name" autocomplete="name"></p>
      <p><label for="email">Email address</label>
        <input id="email" name="email" type="email" autocomplete="email"></p>
      <p><label for="postal">Postal code</label>
        <input id="postal" name="postal-code" autocomplete="postal-code"></p>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The page displays three labeled fields. A browser may offer saved information for these fields when autofill is available.

## Explanation

Autocomplete tokens tell the browser what kind of information a control expects. They do not force the browser to fill a value, and the user remains in control.

## Related lesson

[Read the lesson](../lessons/36-autocomplete-and-autofill.md)
