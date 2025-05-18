# Python Online IDE Client

A modern, feature-rich web-based Python IDE with real-time code execution and AI assistance.

## Features

- **Code Editor**
  - Monaco Editor (VS Code-like experience)
  - Syntax highlighting for Python
  - Dark/Light theme support
  - Resizable layout
  - Keyboard shortcuts

- **Terminal Output**
  - Real-time code execution
  - Colored output
  - Resizable terminal window

- **Input Handling**
  - Interactive input prompts
  - Input history in test area
  - Clear input/output display

- **AI Assistant**
  - ChatGPT-style interface
  - Code block support
  - Copy button for code snippets
  - Real-time responses

- **Code Management**
  - Save/Load code locally
  - Clear editor functionality
  - Keyboard shortcuts for common actions

## Keyboard Shortcuts

- `Ctrl + Enter`: Run code
- `Ctrl + L`: Clear editor
- `Ctrl + S`: Save code
- `Ctrl + O`: Load code

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Client
   ```

2. Open `index.html` in a modern web browser

3. The IDE will automatically connect to the backend server

## Dependencies

- Monaco Editor (CDN)
- xterm.js (CDN)
- Modern web browser with JavaScript enabled

## Browser Support

- Chrome (recommended)
- Firefox
- Edge
- Safari

## Notes

- Code is saved in browser's local storage
- AI chat requires internet connection
- Server must be running for code execution

## License

MIT License 