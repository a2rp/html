# Example 34 - Built-in form validation

## Question

How can native input attributes check required fields and email format?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Built-in form validation</title>
</head>
<body>
  <main>
    <h1>Request an appointment</h1>
    <form>
      <p><label for="email">Email</label>
        <input id="email" name="email" type="email" required></p>
      <p><label for="visitors">Number of visitors</label>
        <input id="visitors" name="visitors" type="number" min="1" max="8" required></p>
      <button type="submit">Continue</button>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The page shows an email field, number field, and button. Submitting an empty form or an invalid email prompts the browser to show a validation message.

## Explanation

Attributes such as required, type=email, min, and max enable built-in constraint checks. These checks improve input guidance but do not replace validation on a server.

## Related lesson

[Read the lesson](../lessons/34-form-validation.md)
