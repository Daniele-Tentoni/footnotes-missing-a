# Missing footnotes label anchor

A footnote label anchor is not rendered when it is inside an HTML tag. There's a change to get it works without writing the anchor by hand?

I'm expecting that `There is a footnote here[^1].` is rendered as:

```html
There is a footnote here<sup id="fnref:1"><a class="footnote-ref" href="#fn:1">1</a></sup>.
```

But no HTML anchor tag is produced:

```html
There is a footnote here[^1].
```
