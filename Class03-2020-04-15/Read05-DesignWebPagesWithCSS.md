# Design Web Pages with CSS

## Summaries of John Duckett's Book, "HTML & CSS":

## Chapter 10 - Introducing CSS:

**CSS** (cascading style sheets) is a formatting language that allows websites to have more elaborate and interesting appearances than is possible with straight HTML. CSS treats each HTML as a box, with styling applied to different parts of that box (background, text, etc..). One uses **selectors** to designate which HTML elements are styled by which **declarations**. Declarations in turn are composed of **properties** (which designate which property of the HTML element is being styled, for example we might specify both the font family and the font color in the same declaration, but using two different properites), and values, which are what is assigned to a given property.

CSS is generally written in a separate document called a **style sheet**, but it can be added to an HTML document directly. The latter is generally only advisable for single page websites, as otherwise the same CSS would need to be added to multiple documents.

The *cascading* part of CSS refers to the fact that the value cascades, with later assignments superseding early ones (with some exceptions). So if an HTML element is given a color assignment at the beginning of a CSS sheet, and then that same HTML element is given a different color at the end, the last color will supersede the first.

## Chapter 11 - Color:

CSS can be used to assign color to HTML elements using color names (like "blue" or "orange"), or RGB, hex code values. CSS3 added RGBA (RGB with an alpha property, for transparency), HSL (hue saturation and lightness), and HSLA (HSL with an alpha property).

Color is one of the fundamental ways of making a website more attractive, readable, and make sure the information you want conveyed is easy to grasp.