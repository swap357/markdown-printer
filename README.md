# Markdown Printer

A lightweight, browser-based markdown editor and printer with live preview. No server required - just open the HTML file in any modern browser. Because sometimes the best web app is the one that doesn't need npm install.

## Features

- **Live Preview**: See rendered markdown as you type (without mysterious 500ms lag)
- **Print & Export**: Generate PDF documents with custom templates that actually look good
- **Import/Export**: Open and save markdown files
- **Multiple Templates**: Choose from academic, business memo, blog, and more
- **Word Counter**: Track document length automatically (for when the professor insists on exactly 500 words)
- **Responsive Design**: Works on desktop and mobile devices
- **Dark/Light Mode**: Automatic theme based on system preferences (because, respect for corneas)

## Usage

1. Open `index.html` in any modern browser
2. Edit markdown in the left panel
3. See instant preview in the right panel
4. Use toolbar buttons to open/save files or export as PDF
5. Enjoy the lack of Electron app consuming 2GB of RAM

## Keyboard Shortcuts

- `Ctrl/⌘ + S`: Save markdown
- `Ctrl/⌘ + O`: Open file
- `Ctrl/⌘ + P`: Print/PDF
- No `Ctrl/⌘ + Z`: Just kidding, we have that too

## Requirements

No installation needed. Built with vanilla JavaScript and uses:
- [Marked](https://marked.js.org/) for markdown rendering
- [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) for PDF generation
- [GitHub Markdown CSS](https://github.com/sindresorhus/github-markdown-css) for styling

## Why Markdown Printer?

Because what the world needed was clearly another markdown editor, but this one sparks joy and doesn't require 857MB of node_modules.
