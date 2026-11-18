# Example 31 - Fieldset and legend

## Question

How can related form options be grouped with a clear caption?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Fieldset and legend</title>
</head>
<body>
  <main>
    <h1>Delivery options</h1>
    <form>
      <fieldset>
        <legend>Choose a delivery method</legend>
        <p><label><input type="radio" name="delivery" value="standard" checked> Standard</label></p>
        <p><label><input type="radio" name="delivery" value="express"> Express</label></p>
      </fieldset>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

A bordered group appears with a caption and two radio options. Selecting one option deselects the other because both share a name.

## Explanation

fieldset groups related form controls. legend gives the group a caption. Each radio control has a label and the shared name makes the choices mutually exclusive.

## Related lesson

[Read the lesson](../lessons/31-fieldset-and-legend.md)
