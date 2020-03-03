# HTML Text fundamentals

All the content resides inside the `<body>` element. It is the content sectioning root.

## Headings, paragraphs and content structuring

* Heading tags are `<h1>, <h2>, <h3>, <h4>, <h5> and <h6>`. Paragraph test is placed inside the HTML element `<p>`.
* Various header elements are used to represent the structural hierarchy. Usually a page contains only one `<h1>` tag. Good practice is to have h2 contain h3 rather than the other way. For instance use h2 for chapter titles and h3 for sections in the chapter and not viceversa.
* General practice is to keep the heading levels to 3 per page.
* Heading play an important role in indexing webpages by search engines.
* Headings helps give the document outline when presented through **screen reader**. **Makes the HTML page more accessible.**

  ```HTML
  <!DOCTYPE html>
  <html lang="en-US">
    <head>
      <title>Sample HTML document</title>
    </head>
    <body>
      <h1>Document heading</h1>
        <h2>Chapter 1</h2>
          <h3>Introduction to Bash</h3>
            <p> Bash is the default shell of GNU operating system. Bash stands for <b>B</b>ourne <b>A</b>gain <b>SH</b>ell, pun intended on the author of unix shell Stephen Bourne.
          <h3>Bash Documentation</h3>
            <p>Bash manual is available at <a href="https://www.gnu.org/software/bash/manual/bash.html" title="Bash manual"></a></p>
    </body>
  </html>
  ```

## Horizontal rule

`<hr>` is a thematic way of separating two paragraphs or logical sections. Though `<p>` element itself is a block level element and so newlines already separate the two paragraphs, `<hr>` is used to **convey a shift in the topic within a section**. This is a **empty html element**.

## Line breaks

When we need to separate content within a paragraph element with new lines(for instance poems with verses), we use `<br>` element. This is an empty html element.

## Lists

Lists in html can either be ordered or unordered. Lists can be nested.

```HTML
<!-- Unordered list -->
<ul>
  <!-- li stands for list item -->
  <li>Apple</li>
  <li>Orange</li>
</ul>
<!-- Ordered list -->
<ol>
  <li>Gold medalist</li>
  <li>Silver medalist</li>
  <li>Bronze medalist</li>
</ol>
```

## Emphasis

* Semantics is very important in Search Engine Optimization and accessbility.
* Text which needs to be emphasized  is usually enclosed within `<em>` tag.
* While rendering, the text is rendered with italics style and screen readers read the text in a different tone.
* If the purpose is just to style the text with italics, then we can use `<i>` or `<span>` element with CSS styling.

## Importance

* Important text is enclosed within `<strong>` tag.
* Browsers display the text as bold and the screen readers read the text in a different tone.
* If the goal is to just display the text in bold and not associating it with any importance, the  we can use `<b>` or `<span>` element with CSS styling.

## Text underline

* Text can be underlined with `<u>`. It is a common practice to underline hyperlinks.

**NOTE**: Elements `<b>, <i> and <u>` don't have any semantics when it comes to accessibility. They just provide presentational value.

## References

* [HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
