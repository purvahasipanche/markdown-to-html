# Markdown to HTML Converter

This project provides a simple, single-page HTML application (`index.html`) to convert a Markdown file (`input.md`) into a styled HTML document. It leverages **Marked.js** for Markdown parsing and **Tailwind CSS** for responsive, modern styling.

## Features

-   **Automatic Conversion**: Loads `input.md` and renders it as HTML.
-   **Responsive Design**: Styles are applied using Tailwind CSS, ensuring the content looks good on various screen sizes.
-   **Clean Output**: Styled Markdown elements (headings, lists, code blocks, images, tables, etc.) for enhanced readability.
-   **Single-File Application**: Everything needed is self-contained in `index.html` (apart from `input.md` itself).

## Getting Started

To use this application, follow these simple steps:

1.  **Download/Clone**: Save `index.html`, `README.md`, `LICENSE`, and most importantly, your Markdown content file named `input.md` into the same directory.
2.  **Prepare `input.md`**: Create or place your Markdown content in a file named `input.md` within the same directory as `index.html`.
3.  **Open `index.html`**: Simply open `index.html` in your web browser. The script will automatically fetch `input.md` and render its content.

### Example `input.md` Structure:

```markdown
# Welcome to Markdown!

This is a paragraph of text. You can make text **bold** or *italic*.

## Features

*   Item 1
*   Item 2
    *   Sub-item A
    *   Sub-item B

### Code Example

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}
greet('World');
```

> This is a blockquote.

[Visit my website](https://example.com)

Here's an image:
<img src="your-image.png">
```

## Technologies Used

-   **Marked.js**: A full-featured markdown parser and compiler written in JavaScript. Built for speed.
-   **Tailwind CSS**: A utility-first CSS framework for rapidly building custom user interfaces.

## License

This project is open-source and available under the [MIT License](LICENSE).