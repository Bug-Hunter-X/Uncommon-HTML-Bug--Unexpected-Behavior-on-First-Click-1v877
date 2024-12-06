# Uncommon HTML Bug: Unexpected Behavior on First Click

This repository demonstrates an uncommon bug related to the initial display style of an HTML element and its impact on a show/hide function. The bug is subtle and may not be immediately apparent.

## Bug Description

The `showHide` function uses `div.style.display` to toggle the visibility of a div.  However, if the `display` style is not explicitly set initially, the first click might behave unexpectedly, and the `else` condition would be triggered inappropriately.

## Bug Solution

The solution involves setting an explicit initial `display` style for the div in CSS, ensuring consistent behavior across all browsers and on the first click.