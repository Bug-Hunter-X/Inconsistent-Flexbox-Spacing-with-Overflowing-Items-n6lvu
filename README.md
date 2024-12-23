# Inconsistent Flexbox Spacing with Overflowing Items

This repository demonstrates an uncommon layout issue that can occur when using CSS Flexbox.  The problem arises when the combined width of flex items exceeds the width of their container.  Some browsers handle this situation inconsistently, leading to unexpected spacing or wrapping behavior.

The `bug.css` file contains the problematic CSS.  The `bugSolution.css` file offers a potential solution.

## Problem

The issue primarily occurs when `justify-content: space-between` is used.  If the items' total width surpasses the container's width, the space-between distribution may not work as expected across all browsers.  This can result in unexpected visual results.