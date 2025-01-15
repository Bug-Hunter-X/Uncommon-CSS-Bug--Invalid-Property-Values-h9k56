# Uncommon CSS Bug: Invalid Property Values

This repository demonstrates an uncommon CSS bug involving an invalid property value that's difficult to detect.  The bug results in unexpected visual behavior, potentially with no obvious errors in the browser's developer console.

## Bug Description
The bug involves using an invalid value for a CSS property, such as a typo, incorrect unit, or unsupported value. This may lead to the property being ignored or rendering unexpectedly.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` and observe the invalid CSS property value.
3. Open `index.html` in a browser.  You will observe the unexpected styling.

## Solution
The solution involves identifying and correcting the invalid CSS property value within `bugSolution.css`.  This fixes the visual issue by ensuring the property accepts a valid value.
