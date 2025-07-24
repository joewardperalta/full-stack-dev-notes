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

The `<span>` element is an inline container used to group text or other inline elements for styling or scripting purposes. It is used for applying CSS styles to part of a text or adding JavaScript hooks like `id` or `class`.

### Example

```html
<p>Hello, <span style="color: red;">Joeward</span>!</p>
```


## Emphasis

The `<em>` element is used to emphasize text, meaning the content it wraps should be read with stress or importanc. The content is rendered in italics.

### Example 

```html
<p>I said <em>now</em>, not later.</p>
```

### Why use `<em>` Instead of `<i>`
- `<em>` has semantic meaning, while `<i>` has visuals only

### Use `<em>` when:
- Highlighting important words or prases for meaning
- Writing accessible and semantically correct HTML


## Strong

The `<strong>` element is used to give strong importance to text. It's a semantic tag that indicates the content is critically important.

### Example

```html
<p>Warning: <strong>Do not share your password.</strong></p>
```

### When to use `<strong>`:
- Highlighting critical information
- Marking important instructions, warnings, or keywords
- Improving accessibility for assistive technologies


## Line Break

The `<br>` is a self closing tag used to move text to the next line without starting a new pararaph.

### Example

```html
<p>
  123 Main St.<br>
  Toronto, ON<br>
  Canada
</p>
```


## Unordered List

An `<ul>` is a list of items that do not follow a specific order. It's commonly used when the order of items doesn't matter. The `<li>` tag is used inside an unordered list to specify an item in a list.

### Example

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```


## Ordered List

The `<ol>` element is used to list items sequentially. The items are numbered instead of bullet points.

### Example

```html
<ol>
  <li>Preheat the oven.</li>
  <li>Mix the ingredients.</li>
  <li>Bake for 30 minutes.</li>
</ol>
```


## Images

The `<img>` element is a self closing tag, meaning it doesn't need a closing tag to be a complete element. It is used to render an image in a web page. The `src` attribute is required to set the image's source such as a URL (Uniform Resource Locator). A URL is a web address or local file path where a file is stored.

### Example

```html
<img 
  src="https://example.com/banner.jpg" 
  alt="Colorful banner promoting the summer sale" 
  width="600" 
  height="200" 
  loading="lazy">
```

### Best Practies:
- Always include meaningful `alt` text
- Use compressed formmts such as `.jpg` for faster loading
- Use `loading="lazy"` for better performance
- Use `srcset` and `sizes` for responsive designs
- Use `<figure>` and `<figurecaption>` for annotated images