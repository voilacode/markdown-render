# Markdown Editor & Renderer

A lightweight, web-based Markdown editor with real-time preview, syntax highlighting, and print-friendly output. Built with HTML, JavaScript, Tailwind CSS, and external libraries like Marked.js and Highlight.js, this tool is perfect for drafting documentation, README files, or any Markdown content.

## Features

- **Split-View Interface**: Edit Markdown on the left and see the rendered output in real-time on the right.
- **Syntax Highlighting**: Code blocks are styled with Highlight.js, with line numbers visible in print output.
- **Synchronized Scrolling**: Scroll the editor or preview, and the other panel aligns automatically.
- **File Drop Support**: Drag and drop `.md` or `.markdown` files to load content instantly.
- **Local Storage**: Automatically saves your Markdown content to the browser's local storage.
- **Copy Functionality**:
  - Copy raw Markdown text to the clipboard.
  - Copy rendered HTML output to the clipboard.
- **Print-Friendly Output**: Generate a clean, printable version with line numbers for code blocks.
- **Responsive Design**: Mobile-friendly header and layout for seamless use on all devices.
- **Instructions Modal**: Access usage instructions via a button in the header.
- **Custom Styling**: DB Markdown-inspired design with Tailwind CSS for a modern, clean look.

## Demo

Try the editor live by opening `index.html` in a web browser or hosting it on a server. A sample Markdown file is included in the repository (`example.md`) to test the file drop feature.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/markdown-editor-renderer.git
   cd markdown-editor-renderer
   ```

2. **Open the Application**:
   - No build process is required. Simply open `index.html` in a modern web browser (e.g., Chrome, Firefox, Edge).
   - Alternatively, serve the project using a local server for a better experience:
     ```bash
     npx http-server
     ```
     Then navigate to `http://localhost:8080`.

## Usage

1. **Editing Markdown**:

   - Type or paste Markdown in the left editor panel.
   - The right preview panel updates in real-time with the rendered output.
   - Use standard Markdown syntax (e.g., `# Heading`, `**bold**`, `code`).

2. **Header Buttons**:

   - **Instructions**: Opens a modal with usage instructions.
   - **Example**: Loads a sample Markdown content to explore features.
   - **Clear**: Clears the editor content.
   - **Copy Markdown**: Copies the raw Markdown text to the clipboard.
   - **Copy HTML**: Copies the rendered HTML to the clipboard.
   - **Print**: Opens a new tab with a print-friendly version of the rendered content.

3. **File Drop**:

   - Drag and drop a `.md` or `.markdown` file into the editor to load its content.
   - Invalid file types will trigger an error notification.

4. **Synchronized Scrolling**:

   - Scroll the editor or preview panel, and the other panel will scroll to align the content.

5. **Printing**:
   - Click the "Print" button to open a new tab with a styled, print-friendly version.
   - Code blocks include line numbers in the print output for better readability.

## Project Structure

```
markdown-editor-renderer/
├── index.html         # Main application file
├── example.md         # Sample Markdown file for testing
├── README.md         # This file
```

## Dependencies

The project uses the following external libraries, loaded via CDN:

- **Tailwind CSS**: For responsive styling.
- **Highlight.js**: For syntax highlighting and line numbers in code blocks.
- **Marked.js**: For parsing Markdown to HTML.
- **Font Awesome**: For icons in the header and notifications.

All dependencies are included in `index.html` via `<script>` and `<link>` tags, so no additional setup is required.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request with a description of your changes.

Please ensure your code follows the existing style and includes appropriate comments.

## Issues

If you encounter bugs or have feature requests, please open an issue on the [GitHub repository](https://github.com/your-username/markdown-editor-renderer/issues). Provide detailed information, including:

- Browser and version.
- Steps to reproduce the issue.
- Screenshots or error messages, if applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

Developed by Krishna Teja.  
Copyright © VoilaCode 2025.

---

Made with ❤️ for Markdown enthusiasts!
