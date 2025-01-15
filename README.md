# Incorrect getElementById usage in HTML
This example demonstrates a common mistake when using `getElementById` in JavaScript within an HTML file. The `getElementById()` method doesn't require a '#' prefix for the ID selector.  The provided code snippet shows the correct and incorrect way of achieving this task.

## Bug
The bug lies in the JavaScript code.  It attempts to access the element with the id 'myDiv' incorrectly, using a '#' symbol before the ID. This will result in the element not being found and therefore, no change in the content.

## Solution
The solution is to remove the '#' prefix from the ID in the `getElementById` method. The corrected JavaScript code correctly accesses the element and modifies its content.