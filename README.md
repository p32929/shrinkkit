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
- **Inspect metadata before you share** — one click reads the EXIF block out of every file in your browser and shows camera make/model, lens, body serial number, owner name, editing software, original timestamp and **GPS latitude/longitude with a map link**. Also reports XMP blocks and PNG text chunks. Free and unlimited.
- **Strips EXIF and GPS metadata** — canvas re-encoding drops every metadata block, so location data in your photos never leaves with them
- Never returns a file bigger than the one you gave it
- One HTML file. No build step, no framework, no tracking, no analytics.
- **Installable PWA** — install it from the browser and it keeps working with no network at all, because there is no server to talk to

## Free vs Pro

The free version compresses **20 images per batch** — enough to try it properly.

**[ShrinkKit Pro](https://p32929.gumroad.com/l/shrinkkit)** — one payment, no subscription:
- Unlimited images per batch
- Batch rename patterns: `{name}` `{n}` `{w}x{h}`
- Settings remembered between visits

## Self-host it

It's one static file — no build step:

```bash
git clone https://github.com/p32929/shrinkkit.git
cd shrinkkit
open index.html          # or drop the folder on any static host
```

## Licence

MIT — see [LICENSE](LICENSE). Read every line before you trust it with your photos, which is rather the point. Pro licences fund the upkeep rather than gate the source.

## Contributing

Contributions are warmly welcomed and greatly appreciated! Whether it's a bug fix, new feature, or improvement, your input helps make this project better for everyone.

Before submitting a pull request, please:

1. Create an issue describing the feature or bug fix you'd like to work on
2. Wait for discussion and approval to ensure alignment with project goals
3. Fork the repository and create your feature branch
4. Submit your pull request with a clear description of changes

This approach helps avoid duplicate efforts and ensures smooth collaboration. Thank you for considering contributing!

## Share

Sharing this repository with your friends is just one click away from here

[![facebook](https://user-images.githubusercontent.com/6418354/179013321-ac1d1452-0689-493f-9066-940cf2302b6e.png)](https://www.facebook.com/sharer/sharer.php?u=https://github.com/p32929/shrinkkit/)
[![twitter](https://user-images.githubusercontent.com/6418354/179013351-7d8d6d1c-4ce2-46ab-bef8-4c4765a1b888.png)](https://twitter.com/intent/tweet?url=https://github.com/p32929/shrinkkit/)
[![tumblr](https://user-images.githubusercontent.com/6418354/179013343-3111f55a-3b90-40c7-8487-9777348672b0.png)](https://www.tumblr.com/share?v=3&u=https://github.com/p32929/shrinkkit/)
[![pocket](https://user-images.githubusercontent.com/6418354/179013334-b095c45f-becf-49f4-9ee1-5a731a9b1f85.png)](https://getpocket.com/save?url=https://github.com/p32929/shrinkkit/)
[![pinterest](https://user-images.githubusercontent.com/6418354/179013331-44cd9206-11b1-4b65-becb-5863b61c828f.png)](https://pinterest.com/pin/create/button/?url=https://github.com/p32929/shrinkkit/)
[![reddit](https://user-images.githubusercontent.com/6418354/179013338-7416ae3f-73ba-4522-86e1-1374d7082d22.png)](https://www.reddit.com/submit?url=https://github.com/p32929/shrinkkit/)
[![linkedin](https://user-images.githubusercontent.com/6418354/179013327-ca7b7102-1da8-4b1c-858f-1a6e5f21bd70.png)](https://www.linkedin.com/shareArticle?mini=true&url=https://github.com/p32929/shrinkkit/)
[![whatsapp](https://user-images.githubusercontent.com/6418354/179013353-f477fa0b-3e6f-4138-a357-c9991b23ff88.png)](https://api.whatsapp.com/send?text=https://github.com/p32929/shrinkkit/)
