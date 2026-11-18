# Example 45 - Popover attributes

## Question

How can a button show and hide a popover using native HTML?

## HTML code

~~~html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Popover attributes</title>
</head>
<body>
  <main>
    <h1>Garden help</h1>
    <button type="button" popovertarget="help-panel">Show help</button>
    <div id="help-panel" popover>
      <p>Choose plants that suit your space and sunlight.</p>
    </div>
  </main>
</body>
</html>
~~~

## Expected output

A button appears. Selecting it opens a popover with help text, and selecting it again closes the popover in supporting browsers.

## Explanation

The popover attribute marks content as a popover. popovertarget connects the button to that content and provides built-in toggle behavior without JavaScript.

## Related lesson

[Read the lesson](../lessons/45-popover-attributes.md)
