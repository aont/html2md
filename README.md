# HTML → Markdown Converter

A lightweight, static HTML page for converting HTML clipboard content into Markdown using
[Turndown](https://github.com/mixmark-io/turndown) with the GFM plugin. It provides a dual-pane
UI for pasting HTML, converting it to Markdown, and copying the result back to your clipboard.

## Features

- Paste HTML from the clipboard into the left textarea.
- Convert HTML to Markdown (GitHub Flavored Markdown rules enabled).
- Copy the generated Markdown to the clipboard.
- Works as a single static file (`public/index.html`) with no build step.

## Usage

1. Open `public/index.html` in a browser.
2. Click **Paste (clipboard → A)** to read HTML/text from the clipboard.
3. Click **Convert (A → Markdown → B)** to generate Markdown.
4. Click **Copy (B → clipboard)** to copy the Markdown output.

> **Note**: Clipboard access requires HTTPS or `localhost`, so use a local web server if
> your browser blocks clipboard access for file URLs.

## Development

This project is a single-page HTML file. Edit `public/index.html` directly to update the UI or
conversion behavior.

## License

See [LICENSE](LICENSE).
