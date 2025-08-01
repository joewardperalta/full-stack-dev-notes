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
  123 Main St.<br />
  Toronto, ON<br />
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
  loading="lazy"
/>
```

### Best Practies:

- Always include meaningful `alt` text for accessibility and seo
- Use compressed formmts such as `.jpg` for faster loading
- Use `loading="lazy"` for better performance
- Use `srcset` and `sizes` for responsive designs
- Use `<figure>` and `<figurecaption>` for annotated images

## Videos

The `<video>` element in HTML is used to eembed a video player into a webpage. it allows visitors to play video files directly in the browser without needing external plugins like Flash.

### Common Attributes:

- `src` - path to the video file
- `controls` - adds playback controls (play, pause, volume, etc.)
- `autoplay` - starts playing the video automatically when the page loads
- `loop` - replays the video in a loop
- `muted` - starts the video with sounds off
- `poster` - specifies an image to show before the video plays
- `width / height` - controls the size of the video player

### Example

```html
<video width="640" height="360" controls poster="thumbnail.jpg">
  <source src="video.mp4" type="video/mp4" />
  <source src="video.webm" type="video/webm" />
  Your browser does not support the video tag.
</video>
```

### Best Practices:

- Include multiple formats: `.mp4`, `.webm`, `.ogg` for compatibility
- Use `controls` to give users control over playback
- Don't autoplay with sound to prevent poor UX
- Use `caption` tracks(`<track>`) for accessibility when needed

## Anchor Link

A link is a way to connect one resource to another, commonly used to
navigate between webpages, import external files like stylesheets, or
link to downloadable content.

### Example

```html
<a href="https://example.com">Visit Example</a>
```

`href` stands for hyperlink reference which tells the browser where
the link goes. This creates a clickable link that takes the user to
`https://example.com`.

### Types of anchor link

#### Internal link

```html
<a href="#about">Go to About Section</a>
```

This example uses the id attribute value of another element as a link.
When users click on this link, it will navigate them to the about section.

#### External link

```html
<a href="https://google.com">Google</a>
```

#### Email link

```html
<a href="mailto:info@example.com">Email Us</a>
```

#### Phone link

```html
<a href="tel:+1234567890">Call Us</a>
```

### Opening links in a new window

The `target` attribute specifies how a link should open.

#### Example

```html
<a href="https://en.wikipedia.org/wiki/Brown_bear" target="_blank"
  >The Brown Bear</a
>
```

A `target` attribute with the value `_blank` instructs the browser to
open the page in a new window.
