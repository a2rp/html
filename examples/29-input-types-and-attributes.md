# Example 29 - Input types and input attributes

## Question

How can different input types collect common kinds of information?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Input types and input attributes</title>
</head>
<body>
  <main>
    <h1>Event registration</h1>
    <form>
      <p><label for="email">Email</label>
        <input id="email" name="email" type="email" required></p>
      <p><label for="guests">Number of guests</label>
        <input id="guests" name="guests" type="number" min="1" max="5" value="1"></p>
      <p><label for="date">Visit date</label>
        <input id="date" name="date" type="date"></p>
      <p><label><input name="updates" type="checkbox"> Email me updates</label></p>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The browser shows an email field, numeric control, date picker, and checkbox. Their exact appearance varies by browser and device.

## Explanation

The input type selects the kind of control and can provide built-in behavior. Attributes such as required, min, max, and value add constraints or an initial value.

## Related lesson

[Read the lesson](../lessons/29-input-types-and-attributes.md)
