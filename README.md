<p align="center">
  <img src="assets/logo.png" alt="vend logo" width="140">
</p>

<h1 align="center">vend</h1>
<p align="center">A gold-and-black AI chat assistant that runs entirely in your browser — as a web app or an Android APK.</p>

<p align="center">
  <a href="https://Phantomdx0.github.io/vend-ai/"><b>Live demo</b></a> ·
  <a href="../../releases/latest"><b>Download APK</b></a>
</p>

---

## Features

- Chat with Google Gemini (bring your own free API key)
- Attach files and images to your messages
- Math rendering with KaTeX
- Voice replies (text-to-speech)
- Optional Wikipedia lookups
- Optional Firebase sync for chat history
- Adjustable reply style: Concise / Detailed
- Mobile-first dark UI

## Quick start

**Web:** open the live demo link above, or download `index.html` and open it in any browser.

**Android:** download `vend-ai-1.0.apk` from [Releases](../../releases/latest), then allow "Install unknown apps" and install.

## Setup

1. Get a free Gemini API key at <https://aistudio.google.com/apikey>
2. Open vend → Settings → paste the key
3. (Optional) Paste your own Firebase config JSON to enable cloud sync

Your keys are stored only in your browser. They are never included in this repository.

## Project structure

```
vend-ai/
├── index.html      # the whole app (HTML + CSS + JS)
├── assets/
│   └── logo.png    # app icon
├── README.md
├── LICENSE
└── .gitignore
```

## Tech

Vanilla HTML/CSS/JS · Gemini API · KaTeX · Firebase (optional) · packaged for Android with WebIntoApp

## Roadmap

- [ ] Screenshots section
- [ ] More voices
- [ ] Export chats

## Author

Built by [@Phantomdx0](https://github.com/Phantomdx0), Hyderabad, India.

## License

MIT — see [LICENSE](LICENSE).
