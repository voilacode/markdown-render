# Markdown Editor & Renderer

A **free, open-source Markdown editor** designed for real-time Markdown rendering, syntax highlighting, and print-friendly output. This lightweight web-based tool is perfect for converting and enhancing Markdown content, including output from AI models like **ChatGPT**, **Claude**, or **Grok**, into beautifully formatted documents. Built with HTML, JavaScript, Tailwind CSS, Marked.js, and Highlight.js, it’s ideal for developers, writers, and anyone working with Markdown.

## Why Use This Markdown Editor?

- **Convert AI-Generated Markdown**: Transform raw Markdown from ChatGPT, Claude, or Grok into polished, readable content with professional styling.
- **Real-Time Preview**: See your Markdown rendered instantly as you type.
- **Open-Source & Free**: Licensed under the MIT License, freely available for personal and commercial use.
- **User-Friendly Design**: Intuitive split-view interface with responsive, mobile-friendly layout.

## Features

- **Split-View Editing**: Write Markdown on the left, view the rendered output on the right.
- **Syntax Highlighting**: Code blocks are styled with Highlight.js, with line numbers in print output.
- **Synchronized Scrolling**: Scroll the editor or preview, and the other panel aligns automatically.
- **File Drop Support**: Drag and drop `.md` or `.markdown` files to load content instantly.
- **Local Storage**: Autosaves your Markdown to the browser for seamless editing.
- **Copy Options**:
  - Copy raw Markdown text to the clipboard.
  - Copy rendered HTML for use in other applications.
- **Print-Friendly Output**: Generate clean, printable documents with line numbers for code.
- **Responsive Interface**: Optimized for desktops, tablets, and mobile devices.
- **Instructions Modal**: Access usage guides via a header button.
- **Modern Styling**: DB Markdown-inspired design with Tailwind CSS for a clean, professional look.

## Demo

Experience the editor live at [https://voilacode.github.io/markdown-render/](https://voilacode.github.io/markdown-render/). Paste or type Markdown, including AI-generated content from ChatGPT, Claude, or Grok, to see it rendered in real-time.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/voilacode/markdown-render.git
   cd markdown-render
   ```

2. **Run the Application**:
   - Open `index.html` directly in a modern browser (e.g., Chrome, Firefox, Edge).
   - For a better experience, serve it with a local server:
     ```bash
     npx http-server
     ```
     Navigate to `http://localhost:8080`.

## How to Use

### Edit Markdown

- Type or paste Markdown in the left editor panel.
- See real-time rendering in the right preview panel.
- Supports standard Markdown syntax (e.g., `# Heading`, `**bold**`, `code`).

### Convert AI-Generated Markdown

- Copy Markdown output from ChatGPT, Claude, or Grok.
- Paste it into the editor to instantly render it with enhanced formatting.
- Use the "Copy HTML" button to export the styled output.

### Header Controls

- **Instructions**: View usage instructions in a modal.
- **Example**: Load sample Markdown to explore features.
- **Clear**: Reset the editor.
- **Copy Markdown**: Copy raw Markdown text.
- **Copy HTML**: Copy rendered HTML.
- **Print**: Open a print-friendly version in a new tab.

### File Drop

- Drag and drop `.md` or `.markdown` files to load content.
- Invalid files trigger an error notification.

### Scroll Sync

- Scroll either the editor or preview panel, and the other syncs automatically.

### Print Output

- Click "Print" to generate a styled, printable document.
- Code blocks include line numbers for clarity.

## Project Structure

```
markdown-render/
├── index.html         # Main application file
├── README.md         # This file
```

## Dependencies

The project uses CDN-loaded libraries:

- **Tailwind CSS**: Responsive styling.
- **Highlight.js**: Syntax highlighting and line numbers.
- **Marked.js**: Markdown-to-HTML parsing.
- **Font Awesome**: Icons for the interface.

All dependencies are embedded in `index.html`, requiring no additional setup.

## Contributing

We welcome contributions to enhance this open-source Markdown editor! To contribute:

1. Fork the repository: [https://github.com/voilacode/markdown-render](https://github.com/voilacode/markdown-render).
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Submit a pull request with a clear description.

Please follow the existing code style and include comments where necessary.

## Reporting Issues

Found a bug or have a feature request? Open an issue on the [GitHub repository](https://github.com/voilacode/markdown-render/issues). Include:

- Browser and version.
- Steps to reproduce.
- Screenshots or error messages.

## License

This project is **free and open-source** under the GNU General Public License v3.0. You are welcome to use, modify, and distribute it, provided that derivative works are also licensed under the GPL.

## Credits

Developed by Krishna Teja.  
Copyright © VoilaCode 2025.

---

Made with ❤️ for Markdown enthusiasts!
