# HTML Structure


## What is HTML structure

The **HTML structure** is the foundation of a web page,
organized in a way that defines what content is shown and
how it's grouped.

Think of it like a tree or a family hierarchy:
- Elements are nested inside each other
- The structure starts from the top `<html>` and branches down into sections like `<head>` and `<body>`.


## Basic HTML Document Structure (Hierarchy)

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Main Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

The breakdown:

1. `<!DOCTYPE html>`
    - Declares the document type (HTML5)

2. `<html>` (Root Element)
    - The top-level container for the whole page

3. `<head>`
    - Contains the meta-information about the page title (shown in the browser tab)
        - Link to CSS
        - Metadata (charset, viewport)
        - Scripts (optional)

## Visual Hierarchy

```php
<html>
├── <head>
│   └── <title>
└── <body>
    ├── <h1>
    └── <p>
```

Each child is **nested** inside its parents. This nesting 
forms the **DOM (Document Object Model)** structure used
by browsers to render the page.


## What is`<!DOCTYPE html>`

The `<!DOCTYPE>` declaration tells the browser what version of HTML to use, so it can render the page correctly. It's not an HTML tag, it's an instruction to the browser from the **Document Type Definition (DTD)**.

### Document Type Definition

Is a set of rules about how HTML should be structured.

### Example

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    div {
      width: 300px;
      padding: 20px;
      background-color: lightblue;
    }
  </style>
</head>
<body>
  <div>This box is rendered in standards mode.</div>
</body>
</html>
```


## The `<html>` Tag

The `<html>` tag is the root element of every HTML document. It wraps all the content of a web page, including the `<head>` and `<body>` sections.

### Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Metadata and links -->
  </head>
  <body>
    <!-- Visible page content -->
  </body>
</html>
```


## The `<head>` Tag

The `<head>` tag in HTML is used to containt meta-information (data about the document) that is not displayed directly on the webpage. It helps the browser understand how to handle the page, including its title, character encoding, styles, scripts, and more.

For more information about metadata navigate to [metadata.md]("05_metadata.md")

### Example

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
  </head>
  <body>
    <h1>Welcome to my website</h1>
  </body>
</html>
```


## Summary

- **HTML** structure is how elements are organized in a web page
- It follows a **hierarchy**, with `<html>` at the root
- Proper structure helps browsers render content correctly and
makes the code easier to read and maintain