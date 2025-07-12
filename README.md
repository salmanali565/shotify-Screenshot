# Shotify Screenshot

📸 **Shotify Screenshot** is a browser extension designed to help you capture, beautify, and edit screenshots quickly and easily. With a powerful in-browser editor, you can add backgrounds, rounded corners, text, and more to create beautiful images for sharing, documentation, or presentations.

---

## Features

- **Full Screen & Area Capture:** Take screenshots of the entire screen or select a specific area.
- **Screenshot Editor:** 
  - Add and style text (font, color, size, bold, italic, underline).
  - Draw and annotate directly on screenshots.
  - Customize backgrounds (solid color or gradients with multiple presets).
  - Adjust padding, rounded corners (for both background and screenshot).
  - Undo/Redo and clear all edits.
  - Save, load, and sync editor settings via Chrome storage.
- **One-Click Download:** Save your edited screenshot as a PNG image.
- **Clipboard Integration:** Copy styled screenshots directly to your clipboard.
- **User-Friendly UI:** Simple and modern interface for seamless screenshot editing.

---

## Installation

1. **Clone or Download:**
   ```sh
   git clone https://github.com/salmanali565/shotify-Screenshot.git
   ```

2. **Load as Unpacked Extension (Chrome):**
   - Go to `chrome://extensions/`
   - Enable **Developer mode**
   - Click **Load unpacked** and select the project folder

---

## Download via Bash (cURL)

You can download this repository as a zip file using cURL:

```bash
curl -L -o shotify-Screenshot.zip https://github.com/salmanali565/shotify-Screenshot/archive/refs/heads/main.zip
```

---

## Usage

1. **Capture a Screenshot:**
   - Use the extension popup to take a full screen or area screenshot.

2. **Edit the Screenshot:**
   - The editor will open automatically.
   - Use the toolbar to add text, draw, or style your screenshot.

3. **Save or Copy:**
   - Click **Save Screenshot** to download.
   - Or copy to clipboard for quick sharing.

---

## File Structure

- `background.js` – Handles extension background tasks and messaging.
- `popup.html`, `popup.css`, `popup.js` – Popup UI for capturing screenshots.
- `editor.html`, `editor.css`, `editor.js` – Main editor interface and logic.
- `content.js` – Injected into tabs to handle screenshot processing and communication.

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests to help improve Shotify Screenshot.

---


## Author

- [salmanali565](https://github.com/salmanali565)
