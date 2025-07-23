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


## Summary

- **HTML** structure is how elements are organized in a web page
- It follows a **hierarchy**, with `<html>` at the root
- Proper structure helps browsers render content correctly and
makes the code easier to read and maintain