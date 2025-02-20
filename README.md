# Uncommon HTML Bug: Incorrect innerHTML Appending

This repository demonstrates a subtle bug related to using `innerHTML` to append text to an HTML element. While `innerHTML` is often used to modify the content of an element, appending to it can lead to unexpected results, particularly when dealing with complex HTML structures. This can be a source of security vulnerabilities.

The `bug.html` file shows the problematic code, while `bugSolution.html` shows the corrected version.  The solution uses `textContent` instead, which is generally safer and more efficient for simple text appends.