# Introduction to JavaScript


## What is JavaScript

**JavaScript** is a powerful programming language used 
to make web pages **interactive** and **dynamic**. It's
one of the core technologies of the web, alongside HTML
and CSS.

While HTML structure the content and CSS styles it, JavaScript
handles user interaction within the website, dynamically update
content, and much more.


## What JavaScript Can Do

- **Interactivity** - responds to clicks, form inputs, key presses, 
etc.
- **Dynamic Content** - updates text, images, or styles without 
reloading the page
- **Form Validation** - checks if input is correct before submitting
- **Animations** - creates smooth transition, sliders, and effects
- **APIs & Data** - fetches and displays data from servers or services
- **Games & Web App** - powers everything from simple games to full
applications like Gmail or Facebook.


## Two Key Building Blocks of JavaScript

- Functions
- Events


## What is an Event

An **event** in JavaScript is something that happens in the browser
that is triggered by the user or the browser itself.

### Common Types of Events

- **click** - the user clicks an element (e.g., a button)
- **mouseover** - the user moves the mouse over an element
- **keydown** - the user presses a key on the keyboard
- **submit** - a form is submitted
- **load** - the page or images finishes loading
- **change** - the value of an input changes

### Example

```html
<button onclick="greet()">Click Me</button>

<script>
    function greet() {
        alert("Hello there!")
    }
</script>
```

In this example:
- The `click` event happens when the button is clicked
- JavaScript runs the `greet()` function in response