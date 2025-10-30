# RichText2Telegram

A web-based converter that transforms rich formatted text into Telegram's markup syntax. Perfect for preserving formatting when copying text from Word, Google Docs, or web pages into Telegram.

## 🚀 Features

- **Dual Version Support**: Convert for Telegram Desktop or Web
- **Rich Text Processing**: Preserve formatting from any source
- **Real-time Conversion**: See results instantly as you type/paste
- **Copy to Clipboard**: One-click copying of formatted text

## 📋 Supported Formatting

### Both Versions
- **Bold**: `**text**`
- **Italic**: `__text__` 
- **Monospace**: ``` ```text``` ```
- **Strikethrough**: `~~text~~`
- **Spoiler**: `||text||`

### Web Version Only
- **Bold + Italic**: `**__text__**`

## 🛠️ How to Use

1. **Select your Telegram version** using the switcher in the header
2. **Copy formatted text** from any application (Word, Docs, web pages)
3. **Paste into the left panel** - formatting will be preserved
4. **Copy the Telegram-formatted text** from the right panel
5. **Paste into Telegram** - formatting will be applied automatically

## 🌐 Live Demo

[Add your GitHub Pages link here]

## 📦 Installation

No installation required! Simply open `richtext2telegram.html` in any modern web browser.

Or host it yourself:
```bash
# Clone the repository
git clone https://github.com/yourusername/richtext2telegram.git

# Serve the file using any web server
python -m http.server 8000
# or
npx http-server