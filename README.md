# Uncommon HTML Bug: Accessing Non-Existent Attribute

This repository demonstrates a subtle HTML bug related to accessing a non-existent attribute of an element.  The bug may not always result in a visible error, but it can cause unpredictable behavior across different browsers and versions. The solution focuses on using a more robust approach to handle attribute access.

## Bug Description:
The bug lies in trying to access an attribute that doesn't exist on an HTML element.  While some browsers may silently ignore it, others might throw an error or return `null`, leading to potential issues.

## How to Reproduce:
1. Open `bug.html` in your browser.
2. Observe the console output for errors or unexpected results.

## Solution:
The provided `bugSolution.html` demonstrates a safer method of checking for attribute existence before accessing it, thereby preventing potential errors.

## Note:
This bug showcases the importance of thorough testing and error handling in web development. While seemingly minor, these subtle issues can affect the functionality of a web application.