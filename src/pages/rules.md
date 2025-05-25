---
title: Rules
permalink: /rules/index.html
description: 'You can use this starter as a template for your blog and you are ready to go! But there are some adjustments you have to make.'
layout: page
---

You solve a grid by putting a value for each cell. Each grid has **exactly one solution**.

Here are the rules:

- Each column contains each possible value exactly once. 
- Each row contains each possible value exactly once.
- Each cage satisfies its mathematical task with the given result.

<img src="/assets/images/rules/rules-4x4.png" alt="alt text" eleventy:widths="200,300" 
loading="eager" decoding="sync">

## Examples

- A cage with 3 cells in a row and **6+** may have 1, 2, 3 in its cells, in any order (1, 2, 3 
  or 1, 3, 2 or 2, 1, 3 or 2, 3, 1 or 3, 1, 2 or 3, 2, 1).
- A cage with 2 cells and **6*** may have two values whose product is 6: 1, 6 or 2, 3 or 3, 2 or 
  6, 1.
- A cage with 2 cells and **6÷** may have 1, 6 or 6, 1.
  This means: The order of the values is not relevant.
- A cage with 2 cells and **1-** may have any two values whose difference is 1, that is 1, 2 or 
  2, 1.

This cage types **÷** and **-** always come with exactly 2 cells as these operations is defined 
for two operants only.
