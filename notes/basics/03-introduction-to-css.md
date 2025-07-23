# Introduction to CSS (Cascading Style Sheets)


## What is CSS

CSS stands for **Cascading Style Sheets**. It's the language used 
to style and design the content on a web page written in HTML.


## What does CSS do
- **Colors** (text, backgrounds, buttons, etc.)
- **Fonts** (size, style, type)
- **Layout** (positioning elements on the page)
- **Spacing** (margins, padding, gaps)
- **Responsiveness** (adapting to different screen sizes)

### Example
```html
<style>
    .greeting {
        color: blue;
        font-size: 20px;
        text-align: center;
    }
</style>

<p class="greeting">Hello, world!</p>
```


## Why is CSS Separate from HTML

**HTML** and **CSS** are separated to follow a key computer 
science principle called **Separation of Conerns**. This means
each language focuses on a **single responsibility**, making
websites easier to manage and scale.

**HTML** is for structure, while **CSS** is for presentation.


## CSS Selector

A **CSS Selector** is a pattern used to target HTML elements
for styling.

### Example

```css
.message {
    color: blue;
    font-size: 20px;
}
```

- `.message` is the CSS selector
- It targets any HTML element with the class `message`


## Visual Rules

**Visual rules** are the actual style instructions inside a CSS block.
They define how the selected elements should look.

### Example

```css
.message {
    color: blue;
    font-size: 20px;
}
```

- The styles inside the `{}` are called visual rules