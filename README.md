# Learn CSS

CSS is the language we use to style a Web page.

This course breaks down the fundamentals of CSS into digestible, easy to understand pieces. Over the next few modules, you'll learn how the core aspects of CSS work and how to use them effectively in your projects.

## CSS Introduction

### What is & Why use CSS?

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files
- CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

Bellow a very basic `CSS` example:

```css
body {
  background-color: lightblue;
}

h1 {
  color: brown;
  text-align: center;
}

p {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 20px;
}
```

## CSS Syntax

!["CSS Syntax"](./assets/css_syntax.png "CSS Syntax")

The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

## CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style. We can divide CSS selectors into five categories:

1. **Simple selectors:** select elements based on name, id, class
1. **Combinator selectors:** select elements based on a specific relationship between them
1. **Pseudo-class selectors:** select elements based on a certain state
1. **Pseudo-elements selectors:** select and style a part of an element
1. **Attribute selectors:** select elements based on an attribute or attribute value

### The CSS element Selector

The element selector selects HTML elements based on the element name.

```css
/* CSS element Selector */
h1 {
  color: darkblue;
}

h2 {
  color: cadetblue;
  text-align: center;
}
```

### The CSS id Selector

The id selector uses the `id` attribute of an `HTML` element to select a specific element. The `id` of an element is unique within a page, so the `id` selector is used to select one unique element!

To select an element with a specific `id`, write a hash (`#`) character, followed by the `id` of the element.

```css
/* CSS id Selector */
#blue_h2 {
  color: blue;
  font-family: "Courier New", Courier, monospace;
}

#red_para {
  color: red;
}
```

### The CSS class Selector

The class selector selects `HTML` elements with a specific class attribute.

To select elements with a specific class, write a period (`.`) character, followed by the class name.

```css
/* CSS class Selector */
.brown {
  color: brown;
}

p.brown {
  font-size: xx-large;
}
```

### The CSS Universal Selector

The universal selector (`*`) selects all HTML elements on the page.

```css
* {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
```

### The CSS Grouping Selector

The grouping selector selects all the `HTML` elements with the same style definitions.

```css
/* CSS Grouping Selector */
h1,
h2,
p {
  font-size: medium;
}
```
