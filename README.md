# 🌐 TranslateTool - Production-Grade Translation Tool

LinguaSwap is a clean, modern, and fully functional language translation web application built as a **single HTML file**. It leverages the free MyMemory API for high-quality translations and the browser's native Web Speech API for text-to-speech functionality.

## ✨ Features

- **Free Translation**: Powered by the MyMemory API (no API key required).
- **25+ Languages**: Support for major global languages with an "Auto Detect" feature.
- **Text-to-Speech (TTS)**: Listen to translations in the target language with an animated waveform indicator.
- **Smart UI/UX**:
  - **Dark & Light Mode**: Seamless theme switching with system preference detection.
  - **Responsive Design**: Optimized for mobile, tablet, and desktop.
  - **Swap Languages**: Quickly switch between source and target languages.
  - **Copy to Clipboard**: One-click copy with visual confirmation.
  - **Keyboard Shortcuts**: Press `Ctrl/Cmd + Enter` to translate instantly.
- **Performance**: Zero external JavaScript dependencies or build tools—just pure, fast HTML/CSS/JS.

## 🚀 Getting Started

### 1. Run Locally
Since this is a single-file application, you have two options:
- **Simple**: Double-click `language-translator.html` to open it in your browser.
- **Development**: Use a local server for the best experience:
  ```bash
  # Using Python
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000/language-translator.html`.

### 2. Free Deployment
You can host this app for free forever using these platforms:
- **Netlify Drop**: Drag and drop the file onto [Netlify Drop](https://app.netlify.com/drop).
- **GitHub Pages**: Upload to a GitHub repo and enable Pages in the settings.
- **Vercel**: Deploy instantly via the Vercel CLI or dashboard.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (CSS Variables, Flexbox, Grid), Vanilla JavaScript (ES6+).
- **API**: [MyMemory Translation API](https://mymemory.translated.net/doc/spec.php).
- **Typography**: Satoshi (Fontshare) and Instrument Serif (Google Fonts).
- **Icons**: Custom SVG icons.

## 📝 API Usage Note
The app uses the MyMemory free tier (1,000 words/day). To increase this limit to 10,000 words/day for free, you can add your email to the API URL in the `translate()` function:
`&de=your-email@example.com`

## ⚖️ License
This project is open-source and free to use for personal or commercial purposes.
