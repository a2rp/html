# Example 30 - Labels and accessible form controls

## Question

How can a visible label be connected to a form control?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Labels and accessible form controls</title>
</head>
<body>
  <main>
    <h1>Sign in</h1>
    <form>
      <p><label for="username">Username</label>
        <input id="username" name="username" autocomplete="username"></p>
      <p><label for="password">Password</label>
        <input id="password" name="password" type="password" autocomplete="current-password"></p>
      <button type="submit">Sign in</button>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The page shows two labeled controls and a button. Selecting a label focuses its associated control.

## Explanation

The label's for value matches the control's id. This association gives the control a programmatic name and makes the label clickable. Placeholder text does not replace a label.

## Related lesson

[Read the lesson](../lessons/30-labels-and-form-controls.md)
