# Basic HTML Tags

## HTML Document Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>

```

## Headings

Used to define headings on a page. `<h1>` is the largest, and `<h6>` is the smallest.

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h6>Smallest Heading</h6>

```

## Paragraphs

Defines blocks of text.

```html
<p>This is a paragraph of text.</p>

```

## Links (Hyperlinks)

Used to navigate to another page or location.

```html
<a href="https://example.com">Click Here</a>

```

## Images

Embeds an image in the document.

```html
<img src="image.jpg" alt="Description of image">

```

## Lists

### Unordered List

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

```

### Ordered List

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>

```

## Tables

Organizes data into rows and columns.

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>

```

## Forms

Collects user inputs.

```html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <button type="submit">Submit</button>
</form>

```

## Div and Span

### `<div>`: Defines a block-level container.

```html
<div>
    This is a block element.
</div>

```

### `<span>`: Defines an inline container.

```html
<span>This is inline text.</span>

```

## Comments

Add notes within the code that are not displayed on the page.

```html
<!-- This is a comment -->

```