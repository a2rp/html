# Example 32 - Textarea, select, option, and datalist

## Question

How can a form offer a multiline message, a fixed choice, and suggestions?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Textarea, select, option, and datalist</title>
</head>
<body>
  <main>
    <h1>Garden help</h1>
    <form>
      <p><label for="topic">Topic</label>
        <select id="topic" name="topic">
          <option value="soil">Soil</option>
          <option value="watering">Watering</option>
        </select></p>
      <p><label for="plant">Plant</label>
        <input id="plant" name="plant" list="plants">
        <datalist id="plants">
          <option value="Tomato"></option>
          <option value="Basil"></option>
        </datalist></p>
      <p><label for="message">Message</label>
        <textarea id="message" name="message" rows="4"></textarea></p>
    </form>
  </main>
</body>
</html>
~~~

## Expected output

The page shows a select menu, a text field that can offer suggestions, and a multiline message box.

## Explanation

select with option provides a set of choices. datalist suggests values while allowing typed input. textarea accepts longer text. Each control has a label.

## Related lesson

[Read the lesson](../lessons/32-textarea-select-and-datalist.md)
