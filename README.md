# dot-and-dash

A .woff font where every character except `-` is replaced with `·`.

Intended to be used with inputs as a simple way to handle visual masking.

## usage

```css
@font-face {
    font-family: DotAndDash;
    src: url('DotAndDash.woff'), url('DotAndDash.woff') format('woff');
}

body {
    font-family: 'DotAndDash', Fallback, sans-serif;
    font-size: 32px;
}
```
