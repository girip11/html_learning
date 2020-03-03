# Document and Website Structure

## Sections of a document

* **Header** - Usually contains heading, optionally website logo
* **Navigation menu** - contains links for navigation within the site. This navigation menu is recommended to be consistent for all pages of the website. Generally navigation menu is consisdered to be part of header and the same content is shared across all the pages.
* **Main content** - contains the content fo the webpage
* **Sidebar** - May contain information about the author of the page, quotes, links to related articles etc.
* **Footer** - copyright notices, contact information, sitemap(quick access to popular content) etc

## HTML tags used for document structuring

* `<header>` - contains header information. This element when placed inside body, contains the page level header information and when placed inside `<article>` or `<section>`, represents the section level header information.

* `<nav>` - navigation bar. `<nav>` semantically cannot contain another `<nav>`. This element contains only the primary navigation links.

* `<main>` is used to enclose the document content area. There should be only one `<main>` element per document and placed as direct child of `<body>`. Within the `<main>` element, `<article>`, `<section>`, `<div>` are all used for sectioning the content.

* `<article>` - contains content that makes sense on its own like a blog post.

* `<section>` - contains content that forms a section of the document, for instance image section, map section in a document, sections in a blog post etc. Good practice to begin section with a heading.

* `<aside>` is used for sidebar content and usually placed inside `<main>`

* `<footer>` - contains the footer information.

* `<div>` - generic container for the content. When a content can't be semantically associated with any of the sectioning elements mentioned above, then the content is enclosed inside `<div>` element.

**NOTE**: `<article>` can be comprised of many `<section>`, or `<section>` can be comprised of many `<article>` based on the context.

## References

* [Document structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
