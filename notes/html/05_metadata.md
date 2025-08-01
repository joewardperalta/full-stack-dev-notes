# HTML Meta Data

**HTML metadata** refers to the data that describes other data on a
webpage.

In HTML, metadata is usually defined in the `<head>` section of the
document using the `<meta>` tag. This data **does not** display on the
page but it is used by browsers, search engines, and social media
platforms to understand and process the webpage.

## Examples

### Set character encoding

```html
<meta charset="UTF-8" />
```

### SEO description

```html
<meta
  name="description"
  content="Learn web development with this complete beginner's guide."
/>
```

### Viewport for mobile responsiveness

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

### Social media sharing (Open Graph - Facebook)

```html
<meta property="og:title" content="Awesome Web Tutorial" />
<meta property="og:description" content="Master web development from sratch." />
<meta property="og:image" content="https://example.com/cover.jpg" />
```

## Summary

HTML metadata helps define how your webpage is understood and
displayed by browsers, crawlers, and platforms. While users don’t see
it directly, it plays a crucial role in accessibility, visibility,
and responsiveness.
