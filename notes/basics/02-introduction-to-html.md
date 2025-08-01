# Introduction to HTML (Hypertext Markup Language)

## What is HTML

**HTML (HyperText Markup Language)** is the foundational language 
used to structure content on the web. It acts as the skeleton of a 
webpage, organizing elements like text, images, buttons, and videos.

## Markup Language

A way to annotate content—like labeling parts of a webpage 
(headings, paragraphs, images)—so browsers know how to display them. 
Just like a teacher marks up an essay with notes, HTML uses tags to 
structure and format content on the web.

## HTML Elements

**HTML tags** are the "markup" in HTML. They act like labels or 
annotations that tell the browser what type of content is inside them. 
Tags are used to **wrap content**, turning it into an **HTML Element**
. For example, a paragraph, heading, or image. The structure includes
an **opening tag**, the **content**, and a **closing tag**.

### Example

#### Paragraph

This example creates a paragraph element with the content 
"*Hello, my name is Joeward*".

```html
<p>Hello, my name is Joeward</p>
```

#### Heading

This example creates a heading 1 element, used for the main title
of the page.

```html
<h1>I'm a Full Stack Web Developer</h1>
```

#### Anchor

This example creates an anchor tag, used to create a link.

```html
<a>Learn more about me</a>
```

#### Button

This example creates a button, used to add user interactivity and 
listen to events—like mouse click.

```html
<button>Send Message</button>
```

## What is Hypertext in HTML

- **H** and **T** stand for **Hypertext**
- Hypertext = text linked to other text via hyperlinks
- Unlike traditional reading (start to end), hypertext 
allows **non-linear navigation**—users browse and choose their 
own path
- It breaks the **traditional constraints** of the written word
by offering interactivity and freedom to explore
- Despite modern features like videos and animations, the web
is still fundamentally a **network of hyperlinked documents**


## HTML Attributes

An **HTML attribute** provides additional information about an 
HTML element. Attributes are always defined in the opening tag
and usually come in **name=value** pairs.

### Adding Hyperlinks

This example uses the **href** (Hyperlink Reference) attribute 
to create a link that will navigate to the homepage of google.

```html
<a href="www.google.com">Google</a>
```