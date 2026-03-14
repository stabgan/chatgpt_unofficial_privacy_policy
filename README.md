# ChatGPT Unofficial Privacy Policy Reference

A minimal static page that links to OpenAI's official privacy policy — intended for use as a privacy-policy URL in apps or extensions that integrate with ChatGPT.

## What It Does

Serves a single HTML page (`index.html`) containing:

- A direct link to [OpenAI's Privacy Policy](https://openai.com/policies/privacy-policy)
- A disclaimer clarifying the page is unofficial and not affiliated with OpenAI

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| 📄 Markup | HTML 5 |
| 🎨 Styling | Inline CSS (system font stack) |

## Usage

No build step required. Open `index.html` in a browser, or deploy to any static host:

```bash
# Local preview
open index.html

# Or serve with Python
python3 -m http.server 8000
```

Host it on GitHub Pages, Netlify, Vercel, or any static file server and point your app's privacy-policy URL to it.

## ⚠️ Known Issues

- The page links to OpenAI's policy — if OpenAI changes the URL, the link will break.
