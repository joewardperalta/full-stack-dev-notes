# Basic HTML Elements

## Body

This element is a core part of an HTML document. It
contains everyting that's visible on the web page like
text, images, buttons, links, and more.

### Example

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Welcome!</h1>
    <p>This is my first website.</p>
  </body>
</html>
```

- **head** - information for the browser (not visible on the page)
- **body** - all content that shows up in the browser window


## Headings

**Headings** in HTML are used to define the titles and subtitles of content on a webpage. They help organize information, improve readability, and give structure to the content—both for users and for search engines (SEO).

### HTML Heading Elements

- `<h1>` - main heading (most important)
- `<h2>` - subheading under `<h1>`
- `<h3>` - subheading under `<h2>`
- `<h4>` - subheading under `<h3>`
- `<h5>` - subheading under `<h4>`
- `<h6>` - smallest heading (least important)

### Best Practices

- Use one `<h1>` per page (usually the page title)
- Use headings to create a clear content hierarchy
- Don't use headings just to make text bigger. Use CSS for styling instead.


## Divs

The `<div>` element stands for **"division"** and is used to group together
other HTML elements. It's a container that doesn't add any visual styling
by itself, but it's extremely useful for structuring, styling, and organizing
content on a web page.

### What it is Used for
- Grouping related content
- Wrapping sections (e.g., header, footer, article)
- Applying CSS styles to a specific area
- Using JavaScript to manipulate parts of the page
- Laying out a page with Flexbox or Grid

### Example

```html
<div class="card">
  <h2>Product Name</h2>
  <p>Price: $19.99</p>
  <button>Buy Now</button>
</div>
```


## Paragraph

The `<p>` tag represents a block of text that is separated from other blocks by vertical spacing. It is a block-level element, meaning it takes up the full width available.

### Example

```html
<p>Hello, my name is Joeward.</p>
<p>I am learning web development.</p>
```


## Span

The `<span>` element is an inline container used to group text or other inlin elements for styling or scripting purposes. It is used for applying CSS styles to part of a text or adding JavaScript hooks like `id` or `class`.

### Example

```html
<p>Hello, <span style="color: red;">Joeward</span>!</p>
```