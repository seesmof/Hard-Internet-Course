# CSS Box Model

A brief description of the repository.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains a single HTML file with inline CSS styling. The HTML file contains an example of using block and inline elements and shows how to style them with CSS. The file includes a simple button styled with CSS.

## Technologies Used

- HTML
- CSS

## Installation

To use this repository, simply clone or download the files and open the HTML file in a web browser.

```bash
git clone https://github.com/seesmof/css-box-model.git
```

## Usage

The HTML file can be used as a reference for creating web pages with block and inline elements. The CSS styles can be used as a starting point for styling those elements.

Here are some examples of the HTML and CSS code in this repository:

```html
<body>
  <h1>Headings Are Block Elements</h1>
  <p>
    Paragraphs are block, too. <em>However</em>, &lt;em&gt; and &lt;strong&gt;
    elements are not. They are <strong>inline</strong> elements.
  </p>
  <p>
    Block elements define the flow of the HTML document, while inline elements
    do not.
  </p>
  <div class="button">Button</div>
</body>
```

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  color: #333;
  background-color: #eee;
}

h1,
p {
  background-color: #dde0e3;
}

em,
strong {
  background-color: #b2d6ff;
}

p {
  padding: 20px 0 20px 10px;
  margin-top: 25px;
  margin-bottom: 50px;
}

strong {
  margin: 20px;
}

h1 {
  padding: 50px;
  border-bottom: 1px solid #5d6063;
}

.button {
  color: #fff;
  background-color: #5995da;
  font-weight: bold;
  padding: 20px;
  text-align: center;
  border: 2px solid #5d6063;
  border-radius: 5px;
  width: 200px;
  margin: 20px auto;
}
```

## Contributing

Contributions to this repository are welcome. To contribute, please fork the repository, create a new branch, make your changes, and submit a pull request.

## License

This repository is licensed under the [MIT License](https://opensource.org/licenses/MIT).
