# CSS Vendor Prefix Bug

This repository demonstrates a common CSS issue: the use of unnecessary vendor prefixes.  Modern browsers generally support standard CSS properties without prefixes, so using outdated prefixes can lead to unexpected results. This example shows how to identify and resolve this problem.

## Bug

The `bug.css` file contains CSS rules with unnecessary vendor prefixes.  This can cause the layout to render incorrectly in some browsers.

## Solution

The `bugSolution.css` file shows the corrected CSS, removing the unnecessary prefixes. The layout should now render consistently across different browsers.