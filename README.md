# Pixlite — JPG/PNG → AVIF/WebP Converter

A fast, privacy-first image converter that runs entirely in your browser. No server, no account, no uploads.

## Features

- Convert JPG/PNG to **AVIF** or **WebP** (or both at once)
- Adjustable **quality slider** (1–100)
- **Lossless mode** toggle for pixel-perfect output
- Animated **before/after size comparison** per file
- **Batch conversion** with ZIP download
- Zero dependencies served to the user (Canvas API only)

## Privacy

Everything runs client-side via the browser's Canvas API. Your images never leave your device.

## Browser Support

| Format | Chrome | Firefox | Safari |
|--------|--------|---------|--------|
| WebP   | 32+    | 65+     | 14+    |
| AVIF   | 85+    | 93+     | 16+    |

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/pixlite)

Or manually:
```bash
npm i -g vercel
vercel
```

## Local development

Just open `index.html` in a browser — no build step required.

## License

MIT
