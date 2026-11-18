# Example 33 - Buttons and form actions

## Question

How do button types change their behavior inside a form?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Buttons and form actions</title>
</head>
<body>
  <main>
    <h1>Form buttons</h1>
    <form>
      <label for="note">Note</label>
      <input id="note" name="note">
      <p><button type="submit">Save</button></p>
      <p><button type="reset">Clear form</button></p>
      <p><button type="button">Other action</button></p>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

Three buttons appear. Save submits the form, Clear form resets its controls, and Other action has no built-in action.

## Explanation

Inside a form, a button defaults to submit unless its type is set. Use type=button for a button that should not submit, usually when another behavior is provided.

## Related lesson

[Read the lesson](../lessons/33-buttons-and-form-actions.md)
