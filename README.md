<p align="center">
  <img src="./assets/mdviewer.svg" alt="MDviewer logo" width="128">
</p>

<h1 align="center">MDviewer</h1>

<p align="center">
  A lightweight macOS app that opens Markdown files as clean, print-ready documents.
</p>

<p align="center">
  <a href="https://github.com/JackYoung27/mdviewer/releases/latest">Download</a>
  &nbsp;&middot;&nbsp;
  <a href="#features">Features</a>
  &nbsp;&middot;&nbsp;
  <a href="#install">Install</a>
</p>

---

<p align="center">
  <img src="./assets/demo.gif" alt="MDviewer demo" width="720">
</p>

## Features

- **Native macOS** — Cocoa + WKWebView, launches instantly, under 1 MB
- **Print-ready typography** — serif body, clean headings, proper spacing
- **PDF export** — `Cmd+Shift+E` to save, `Cmd+P` to print
- **Live reload** — re-renders automatically when the file changes on disk
- **GitHub Flavored Markdown** — tables, task lists, fenced code blocks
- **Secure** — HTML sanitized with [DOMPurify](https://github.com/cure53/DOMPurify), strict Content Security Policy
- **Finder integration** — registers as default `.md` handler; double-click to open
- **Tabbed windows** — multiple documents in one window
- **Local-first** — no network calls, no telemetry, no accounts

## Install

### Download

1. Grab `Markdown.Viewer.app.zip` from [Releases](https://github.com/JackYoung27/mdviewer/releases/latest)
2. Unzip, drag to `/Applications`
3. First launch: right-click → **Open** (required once for unsigned apps)

### Build from source

```bash
git clone https://github.com/JackYoung27/mdviewer.git
cd mdviewer
./build.sh          # builds to dist/Markdown Viewer.app
./install.sh        # optional: copies to /Applications and sets as default handler
```

Requires Xcode Command Line Tools (`xcode-select --install`).

## Keyboard Shortcuts

| Action | Shortcut |
|---|---|
| Open file | `Cmd+O` |
| Reload | `Cmd+R` |
| Print | `Cmd+P` |
| Export PDF | `Cmd+Shift+E` |
| Close window | `Cmd+W` |

## Screenshots

| Document view | Code blocks | Checklists |
|---|---|---|
| ![doc](./assets/screenshot-doc.png) | ![code](./assets/screenshot-code.png) | ![checklist](./assets/screenshot-checklist.png) |

## License

[MIT](./LICENSE)
