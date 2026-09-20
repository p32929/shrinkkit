# ShrinkKit

**Bulk image compressor that never uploads your photos.**
Compress, resize, convert and strip EXIF/GPS from hundreds of images at once — entirely inside your browser.

### 👉 [Use it now — p32929.github.io/shrinkkit](https://p32929.github.io/shrinkkit/)

No signup. No server. No upload. Works offline after the first load.

## Why

Squoosh does one image at a time. TinyPNG uploads your files to somebody else's server and charges a subscription for bulk. ShrinkKit does the whole folder at once, on your own machine, and never sends a byte anywhere.

## What it does

- Drop a whole folder of images → get them back compressed, as individual files or one ZIP
- WebP / JPEG / PNG output, or keep the original format
- Quality slider, optional max width/height resize
- **Strips EXIF and GPS metadata** — canvas re-encoding drops every metadata block, so location data in your photos never leaves with them
- Never returns a file bigger than the one you gave it
- One HTML file. No build step, no framework, no tracking, no analytics.

## Free vs Pro

The free version compresses **5 images per batch** — enough to try it properly.

**[ShrinkKit Pro](https://p32929.gumroad.com/l/shrinkkit)** — one payment, no subscription:
- Unlimited images per batch
- Batch rename patterns: `{name}` `{n}` `{w}x{h}`
- Settings remembered between visits

## Self-host it

It's one static file. Clone and open `index.html`, or drop it on any static host.

## Licence

Source-available for inspection and self-audit — read every line before you trust it with your photos, which is rather the point. Pro licences fund the upkeep.
