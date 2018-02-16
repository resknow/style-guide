# Markup Style Guide

### Indenting
At Resknow, we intend 4 spaces.

```css
.my-class {
    padding: 1rem;
}
```

```html
<div class="my-class">
    <h1>Hello World.</h1>
</div>
```

## HTML

### Document Type

All Resknow projects should use the HTML5 spec.

```html
<!doctype html>
```

### Block Elements

Block elements should always have their opening and closing tags on their own line. With the exception of `<p>`.

```html
<article>
    <header>
        <h2>Hello World</h2>
    </header>
    <main>
        <p>Some interesting things here.</p>
    </main>
</article>
```

### Inline Elements

Inline elements should be on a single line.

```html
<strong>Look at me I'm all bold.</strong>
```

### Void Elements

Void elements, like `<br>` should not be closed.

##### Good
```html
<br>
```

##### Bad
```html
<br />
```

### Semantics & Accessibility

Use elements for what they have been created for. For examples use heading elements (`h1, h2` etc.) for headings, `p` for paragraphs and so on.


### Links & Buttons

Use the `a` tag if it links to something. Otherwise, use a `button`.

-----

Thanks to Wixel for the inspiration, see https://github.com/Wixel/Markup-Style-Guide
