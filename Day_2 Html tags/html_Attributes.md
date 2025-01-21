# HTML Attributes

HTML attributes are used to define the characteristics of an HTML element. They are placed within the element's opening tag and consist of two parts: the name and the value.

- **Name**: Specifies the property for that element.
- **Value**: Sets the value of that property for the element.

## Types of HTML Attributes

There are three main types of HTML attributes:

### Core Attributes

These are basic attributes that can be applied to most HTML elements. Examples include:

- `id`
- `class`
- `style`

### Internationalization Attributes

These attributes help adapt the document to different languages and regions. Examples include:

- `lang`
- `dir`

### Generic Attributes

These attributes provide additional information about the element but don't necessarily affect its appearance or behavior. Examples include:

- `data-*` attributes (used for storing custom data private to the page or application).

## Core Attributes

Core attributes are some of the most widely used attributes in HTML. There are four main types:

### ID Attribute

The `id` attribute is used to assign a unique identifier to an HTML element. Each element with an `id` has its own unique identity, similar to how each individual has a unique identity. Multiple elements cannot have the same `id`.

**Example:**

```html
<p id="html">This is an HTML tutorial</p>
<p id="python">This is a Python tutorial</p>

```

In this example, the `id` attribute helps to distinguish between two paragraphs by having different values: `html` and `python`.

### Class Attribute

The `class` attribute is used to associate an HTML element with a particular class, typically for styling or JavaScript manipulation. Unlike the `id` attribute, the `class` attribute is not unique, and multiple elements can share the same class.

### Title Attribute

The `title` attribute provides additional information about an element and is often displayed as a tooltip when the mouse hovers over it.

**Example:**

```html
<h4 title="hello, motto">Title attribute</h4>

```

### Style Attribute

The `style` attribute allows for inline styling of HTML elements. It is used in conjunction with CSS properties to directly style individual elements within the HTML code.