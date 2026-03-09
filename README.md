<p align="center">
  <img src="./mdviewer.svg" alt="MDviewer logo" width="128">
</p>

# MDviewer

A lightweight native macOS Markdown preview app. Opens `.md` files in a clean window with print and PDF export.

## Build

```bash
./build.sh
```

Output: `dist/Markdown Viewer.app`

## Install

```bash
./install.sh
```

Copies to `/Applications` and registers as the default Markdown handler.

On first launch, right-click the app and choose **Open** to satisfy Gatekeeper.

## License

[MIT](./LICENSE)
