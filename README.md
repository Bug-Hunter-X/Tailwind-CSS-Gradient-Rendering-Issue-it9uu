# Tailwind CSS Gradient Bug

This repository demonstrates a common issue encountered when using Tailwind CSS gradients: unexpected rendering or missing gradients.  The bug arises from either incorrect gradient syntax or conflicts with other CSS rules.

## Bug Description
The `bg-gradient-to-r` utility is used to create a linear gradient from left to right. However, if the `to` color is missing or incorrectly specified, the gradient won't render as expected, or might not render at all.  This can also happen if there are conflicting CSS stylesheets or improperly configured Tailwind setup.

## Solution
The solution is to verify the `from` and `to` colors in the gradient are correctly specified and there are no conflicts. Ensure that Tailwind CSS is correctly installed and configured.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a browser.  You will observe an unexpected gradient rendering or a missing gradient.
3. Open `solution.html` to see the corrected code.