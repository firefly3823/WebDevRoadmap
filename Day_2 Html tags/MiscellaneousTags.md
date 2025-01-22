## HTML `<code>` Tag

The `<code>` tag is used to display code snippets on a webpage. It is helpful for showcasing both inline and block-level code.

- **Inline Code**: This is used for displaying small code segments within a line of text.

```html
<code>Your code here</code>
```

- **Multiline Code**: When you need to display larger code blocks, it's common to combine the `<code>` tag with the `<pre>` tag. The `<pre>` tag preserves the formatting, like line breaks and spaces.

```html
<pre><code>Your code here</code></pre>
```

## HTML Semantic Tags

HTML5 introduced semantic tags that help describe the structure of a webpage in a more meaningful way. These tags improve accessibility, SEO, and readability for both developers and browsers.

- **Common Tags**:
   - `<header>`: Defines the top section of a webpage, often containing headings, logos, and navigation menus.
   - `<nav>`: Represents navigation links, often used to create menus.
   - `<article>`: Represents self-contained content such as a blog post, news article, or similar standalone content.
   - `<footer>`: Contains footer information, typically including copyright, contact details, etc.
   - `<main>`: Denotes the primary content area of the page.
   - `<aside>`: Represents content that is related but separate from the main content (e.g., sidebars or additional info).

## HTML `<canvas>` Tag

The `<canvas>` tag is used for drawing graphics and dynamic content using JavaScript. It is widely used in game development, visualizations, and interactive web graphics.

- **Syntax**: To define a canvas, you simply need to specify its width and height:

```html
<canvas id="myCanvas" width="200" height="100"></canvas>
```

## HTML Global Attributes

HTML Global Attributes are attributes that can be applied to any HTML element. These provide additional functionality and control over elements.

- **Examples**:

- `class`: Specifies one or more class names for an element, useful for styling or scripting.

```html
<div class="container">This is a container</div>
```

- `id`: Defines a unique identifier for an element, allowing for direct referencing in scripts or styles.

```html
<span id="unique">Unique Element</span>
```

- `data-*`: Custom attributes for storing extra data on elements, used for data manipulation in JavaScript.

```html
<div data-user="123">Custom Data</div>
```

## HTML Entities

HTML entities are used to display special characters that are either reserved in HTML or not easily typed on a keyboard. They are represented as `&` followed by the entity name or code, ending with a semicolon.

- **Common Entities**:
   - `&lt;` for `<`
   - `&gt;` for `>`
   - `&copy;` for `©`
   - `&nbsp;` for a non-breaking space.

Example usage:

```html
<p>Copyright &copy; 2023.</p>
```

## HTML Quotation Tags

HTML provides two tags specifically for quoting text:

- **`<blockquote>`**: Used for long, block-level quotes, often from external sources. It's commonly indented.

```html
<blockquote cite="source-url">Long quote here</blockquote>
```

- **`<q>`**: Used for inline quotes within a sentence or text.

```html
The philosopher said, <q cite="source-url">The unexamined life is not worth living.</q>
```

## Obsolete HTML Tags

Some HTML tags are now considered obsolete and are not recommended for use. These tags may not work in modern browsers, and their usage could result in accessibility or compatibility issues.

- **Obsolete Tags**:
   - `<font>`: Was used to define text color, size, and font. It is now replaced by CSS for styling.
   - `<center>`: Was used to center-align elements. CSS should now be used for centering.
   - `<u>`: Was used for underlining text. CSS should now be used for styling text with underline.

Modern alternatives:

```html
<span style="color:red; font-size:16px; font-family:verdana;">This is some text</span>
```

## Character Sets

Character sets define the characters available for text representation in HTML. Choosing the right character set ensures that text is displayed correctly across different browsers and platforms.

- **Common Character Sets**:
   - `UTF-8`: A universal character set that supports a wide range of characters from multiple languages.
   - `ISO-8859-1`: A character set for the Western alphabet.

You can specify the character set in the `<meta>` tag within the `<head>` section of an HTML document:

```html
<meta charset="UTF-8">
```
