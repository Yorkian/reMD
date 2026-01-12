# reMD - Markdown Renderer

A Chrome extension that detects and renders Markdown content displayed as plain text on web pages.

## Features

- **Smart Detection**: Automatically identifies Markdown syntax (headers, lists, code blocks, links, etc.) displayed as plain text
- **One-Click Render**: Converts detected Markdown content to beautifully formatted rich text
- **Toggle View**: Easily switch between original text and rendered view
- **Auto Scan**: Option to automatically detect Markdown on page load (enabled by default)
- **Dark Mode**: Automatically adapts to system theme

## Supported Markdown Syntax

- Headers (`# ## ###` etc.)
- Bold (`**text**` or `__text__`)
- Italic (`*text*` or `_text_`)
- Code blocks (` ``` `)
- Inline code (`` `code` ``)
- Links (`[text](url)`)
- Images (`![alt](url)`)
- Unordered lists (`- item` or `* item`)
- Ordered lists (`1. item`)
- Blockquotes (`> text`)
- Horizontal rules (`---`)
- Strikethrough (`~~text~~`)
- Task lists (`- [ ] task`)
- Tables

## Installation

### From Source (Developer Mode)

1. Download or clone this repository

2. Open Chrome and navigate to the extensions page:
   - Enter `chrome://extensions/` in the address bar
   - Or go to Menu → More Tools → Extensions

3. Enable "Developer mode" in the top right corner

4. Click "Load unpacked"

5. Select the `reMD` folder from this project

6. Done! You'll see the reMD icon in your browser toolbar

7. Or install from the [Chrome Web Store](https://chromewebstore.google.com/detail/remd-markdown-renderer/gnfdcineaggoebhfgpghaicknbbonnil)

## Usage

1. **Scan & Render**: Click the reMD icon in the toolbar, then click "Scan & Render"
2. **Toggle View**: Hover over rendered content and click the toggle button to switch between original/rendered view
3. **Auto Scan**: Toggle "Auto Scan" in the popup to enable/disable automatic detection on page load

## Use Cases

- GitHub Issues / Discussions showing raw Markdown
- Forums and comment sections displaying Markdown as plain text
- Chat tools (Slack, Discord web) with unrendered Markdown messages
- Any webpage showing Markdown source as plain text

## File Structure

```
reMD/
├── manifest.json      # Extension configuration
├── content.js         # Content script (core detection and rendering logic)
├── content.css        # Rendered content styles
├── popup.html         # Popup interface
├── popup.css          # Popup styles
├── popup.js           # Popup logic
├── marked.min.js      # Markdown parsing library
└── icons/             # Icon files
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

## Tech Stack

- Chrome Extension Manifest V3
- [marked.js](https://github.com/markedjs/marked) - Markdown parsing
- Vanilla JavaScript (no framework dependencies)

## Notes

- The extension automatically skips already formatted content (code blocks, rendered Markdown, etc.)
- Detection is based on feature scoring and may occasionally have false positives
- Some websites may restrict extension functionality due to security policies

## Development

To modify the code:

1. Go to `chrome://extensions/`
2. Click the refresh button on the reMD extension card
3. Refresh the target webpage to see changes

## License

MIT License
