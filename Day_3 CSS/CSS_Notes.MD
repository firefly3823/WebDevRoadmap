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