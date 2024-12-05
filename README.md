# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a common, yet easily overlooked, error in JavaScript when interacting with HTML elements. The bug lies in a simple typo within the `getElementById` method, preventing the intended modification of the HTML content.

## Bug Description

The provided HTML file attempts to change the innerHTML of a div element with the ID "myDiv".  However, due to a missing 'i' in `getElementByid`, the JavaScript code fails to correctly select the element and therefore fails to modify its content. This can result in unexpected behavior and require some debugging to resolve.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Inspect the page's source code and you will notice that the div element's content does not change.