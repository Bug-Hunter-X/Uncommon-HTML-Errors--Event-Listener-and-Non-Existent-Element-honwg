# Uncommon HTML Errors

This repository demonstrates a couple of uncommon errors that can occur in HTML, specifically related to event listeners and accessing elements that do not exist in the DOM.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file provides the corrected code.

**Error 1:** Incorrect event listener assignment.

The code incorrectly assigns an event listener using the assignment operator (=) instead of `addEventListener`.  This approach may work in certain cases, but it lacks the flexibility and capability to manage multiple listeners on the same element, often leading to unexpected behavior.

**Error 2:** Attempting to access a non-existent element.

The code attempts to access an element that does not exist in the DOM, resulting in a runtime error.

**Solution:** Correct event listener implementation.

The `bugSolution.html` shows the proper use of `addEventListener` to add an event listener.

This example is intended to help developers better understand how to handle event listeners and avoid runtime errors when working with HTML.