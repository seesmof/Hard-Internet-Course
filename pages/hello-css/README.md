# Hello, CSS!

This is a simple example of how CSS can be used to style HTML elements. The repository contains two files, `hello-css.html` and `dummy.html`.

## `hello-css.html`

`hello-css.html` is a basic HTML file with some elements styled using CSS. The file contains:

- A heading (`<h1>`) that says "Hello, CSS".
- A paragraph (`<p>`) that explains what CSS is and links to `dummy.html`.
- Another heading (`<h2>`) that says "List Styles".
- A paragraph (`<p>`) that explains how to style unordered and ordered lists, followed by examples of each type of list.
- Two stylesheets that apply some basic styles to the elements in the file.

### Styles

The styles in `hello-css.html` are defined in the `<style>` element in the `<head>` of the file. The styles include:

- A `font-family` of `Arial, Helvetica, sans-serif` applied to the `body` element.
- A `color` of `#414141` applied to the `body` element.
- A `background-color` of `#eee` applied to the `body` element.
- A `font-size` of `17px` applied to the `body` element.
- A `font-size` of `2em` applied to all `<h1>` elements.
- A `font-size` of `1.6em` applied to all `<h2>` elements.
- A `font-family` of `Arial, Helvetica, sans-serif` applied to all headings (`<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`).
- A `color` of `inherit` applied to all links (`<a>`).
- A `color` of `#666` and a `transition` of `all 0.5s ease-in-out` applied to all links (`<a>`) when hovering over them.

The styles for the list styles are also defined in the `<style>` element in the `<head>` of the file. The styles include:

- A `list-style-type` of `disc` applied to the first `<li>` element in the unordered list (`<ul>`) and a `list-style-type` of `circle` applied to the second `<li>` element. The third `<li>` element has a `list-style-type` of `square`.
- A `list-style-type` of `decimal` applied to the first `<li>` element in the ordered list (`<ol>`). The second `<li>` element has a `list-style-type` of `lower-roman`, the third `<li>` element has a `list-style-type` of `upper-roman`, the fourth `<li>` element has a `list-style-type` of `lower-alpha`, the fifth `<li>` element has a `list-style-type` of `upper-alpha`, and the sixth `<li>` element has a `list-style-type` of `square`.

## `dummy.html`

`dummy.html` is a dummy page that links back to `hello-css.html`. The file contains:

- A heading (`<h1>`) that says "Dummy".
- A paragraph (`<p>`) that explains what the page is for and links back to `hello-css.html`.
- Another paragraph (`<p>`) that includes a link to a non-existent page with a line-through style applied to it.

### Styles

The styles in `dummy.html` are inherited from the styles in `hello-css.html`.

Thank you for checking out this repository!
