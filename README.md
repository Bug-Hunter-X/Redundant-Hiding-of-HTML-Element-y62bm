# Redundant Hiding of HTML Element

This repository demonstrates an uncommon bug in HTML related to hiding an element using both `display: none` and `visibility: hidden` in JavaScript.  While both properties can hide an element, using them together is redundant and may introduce unexpected results.

## Bug Description

The `bug.html` file contains a simple HTML structure with a div element.  The JavaScript code attempts to hide the div by setting both its `display` and `visibility` styles to `"none"` and `"hidden"` respectively.  This is unnecessary and potentially problematic.

## Solution

The `bugSolution.html` file demonstrates the correct way to hide the element, using only one of these properties.