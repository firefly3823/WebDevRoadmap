## What is CSS?

CSS stands for Cascading Style Sheets. It is a stylesheet language that is used to describe the visual presentation of a web page written in HTML (Hypertext Markup Language).
HTML creates the structure of the page, while CSS adds styling to that structure.
CSS was created by Håkon Wium Lie to enhance the visual aspects of websites. Initially, websites were mainly used by researchers and lacked visual appeal. As websites became more widespread, the need for better design grew.

**How does CSS work?**
CSS operates by selecting HTML elements and applying styles to them. Styles dictate the appearance of elements on a webpage. You can target HTML elements, classes, or IDs, defining properties like colors, fonts, margins, etc.

```sh
/* Example of a CSS rule */
selector {
    property: value;
}
```

- **Key Features of CSS:**
   - Styles and layouts of web pages.
   - Works alongside HTML and XML documents.
   - Enables responsive design for different screen sizes.
   - Supports interactive effects like hover states and animations.
   - CSS is now modularized, with ongoing updates rather than version numbers.
   - Allows reusability of the same rules across multiple HTML documents.

## How CSS Works?

**The following steps will help us understand more about CSS working :**

- The user types the URL and clicks enter.
- The browser makes a fetch request to the server.
- HTML is fetched from the server.
- HTML is converted into a DOM. In the DOM, each tag is considered a node.
- The browser fetches all the related files and assets that are linked to that HTML, such as external CSS, fonts, images, etc.
- The browser then parses the CSS and groups it based on the selectors, which can be tags.
- Each CSS is attached to its respective node. In this phase, CSS gets attached to its respective node. This is called a render tree.
- The render tree is the well-structured, well-arranged DOM node that will appear on the screen.
- The well-structured, custom-designed website is presented on the screen. This is called painting.

## What is a DOM?

A DOM is like a tree structure representation of all the tags and elements on the page. Each part of a web page, like headings, paragraphs, images, buttons, etc., will be part of the tree.

Example :

```sh
html
├── head
│   ├── title
│   └── meta
└── body
    ├── header
    │   ├── h1
    │   └── nav
    │       ├── ul
    │       │   ├── li
    │       │   └── li
    │       └── a
    ├── main
    │   ├── section
    │   │   ├── h2
    │   │   └── p
    │   ├── article
    │   │   └── p
    │   └── aside
    │       └── p
    └── footer
        └── p 
```

## Ways to add CSS into Website

- Inline CSS
- Internal CSS
- External CSS

**Inline CSS**

Inline CSS is used to add custom properties to specific elements. The added style will only reflect on that particular element only.

To use inline CSS, Insert the "style" attribute within the HTML element's opening tag.

```sh
<h1 style="color: purple;">HEADING 1</h1>
<h2>THIS IS A HEADING</h2>
```

**Internal CSS**

Internal CSS is used to apply custom style to the multiple elements on the same page. The style can be used throughout the HTML page.
Internal CSS is defined in a style block, which will be inside the head section.

```sh
<head>
    <style>
        p {
            color: red;
        }
    </style>
</head>

<body>
    <h1>CodeWithHarry</h1>
    <p>Paragraph</p>
    <p>this is a paragraph</p>
</body>

</html>
```

**External CSS**

- External CSS works similarly to internal CSS but with a twist. Instead of adding the styles within the HTML file, we create a separate file with .css extension. This file will hold all the styling details. Then, we link this file to the HTML page, giving it the instructions on how to look. 

Linking External Style sheet:

```sh
<html lang="en">

<head>
    <title>title</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <p>Paragraph</p>
    <p>I'm a Developer</p>
</body>

</html>
```

# CSS Selectors

CSS Selectors are patterns used to select and style HTML elements. This document provides an overview of the various CSS selectors and how they can be used to create effective styles for your website.

---

## **1. Basic Selectors**

### **Universal Selector (`*`)**
Selects all elements in the document.
```css
* {
  margin: 0;
  padding: 0;
}
```

### **Type Selector (`tagname`)**
Selects all elements of a specific type (e.g., `p`, `div`, `h1`).
```css
p {
  color: blue;
}
```

### **Class Selector (`.classname`)**
Selects all elements with a specific class attribute.
```css
.container {
  padding: 10px;
  background-color: #f4f4f4;
}
```

### **ID Selector (`#id`)**
Selects the element with a specific ID (unique for each document).
```css
#header {
  background-color: gray;
  color: white;
}
```

---

## **2. Combinators**

### **Descendant Combinator (`A B`)**
Selects all elements `B` that are descendants of element `A`.
```css
div p {
  font-size: 16px;
}
```

### **Child Combinator (`A > B`)**
Selects all elements `B` that are direct children of element `A`.
```css
ul > li {
  list-style: none;
}
```

### **Adjacent Sibling Combinator (`A + B`)**
Selects the element `B` immediately following element `A`.
```css
h1 + p {
  margin-top: 10px;
}
```

### **General Sibling Combinator (`A ~ B`)**
Selects all elements `B` that are siblings of element `A`.
```css
h1 ~ p {
  color: gray;
}
```

---

## **3. Attribute Selectors**

### **[attribute]**
Selects elements with a specific attribute.
```css
[title] {
  color: green;
}
```

### **[attribute=value]**
Selects elements with a specific attribute value.
```css
[type="text"] {
  border: 1px solid black;
}
```

### **[attribute^=value]**
Selects elements whose attribute value starts with a specific value.
```css
[href^="https"] {
  color: blue;
}
```

### **[attribute$=value]**
Selects elements whose attribute value ends with a specific value.
```css
[src$=".jpg"] {
  border: 1px solid gray;
}
```

### **[attribute*=value]**
Selects elements whose attribute value contains a specific value.
```css
[class*="btn"] {
  padding: 5px;
}
```

---

## **4. Pseudo-classes**

### **`:hover`**
Styles an element when it is hovered over by the user.
```css
a:hover {
  text-decoration: underline;
}
```

### **`:nth-child(n)`**
Selects the nth child of its parent element.
```css
li:nth-child(2) {
  color: red;
}
```

### **`:first-child` and `:last-child`**
Selects the first or last child of its parent element.
```css
p:first-child {
  font-weight: bold;
}

p:last-child {
  color: blue;
}
```

### **`:not(selector)`**
Selects elements that do not match the given selector.
```css
div:not(.active) {
  opacity: 0.5;
}
```

---

## **5. Pseudo-elements**

### **`::before` and `::after`**
Used to insert content before or after an element’s content.
```css
p::before {
  content: "Note: ";
  font-weight: bold;
}

p::after {
  content: " © 2025";
}
```

### **`::first-line`**
Styles the first line of a block of text.
```css
p::first-line {
  font-size: larger;
  text-transform: uppercase;
}
```

---

## **6. Grouping Selectors**
Combine multiple selectors to apply the same style.
```css
h1, h2, h3 {
  font-family: Arial, sans-serif;
  color: #333;
}
```

---

## **7. Specificity and Priority**
### Order of specificity (from lowest to highest priority):
1. **Universal selector (`*`)**
2. **Type selectors (`h1`, `p`, etc.)**
3. **Class selectors (`.classname`), Attribute selectors (`[type="text"]`), Pseudo-classes (`:hover`)**
4. **ID selectors (`#id`)**
5. **Inline styles**

If two rules apply to the same element, the one with higher specificity takes precedence.

---