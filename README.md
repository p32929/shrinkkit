# ShrinkKit

**Bulk image compressor that never uploads your photos.**
Compress, resize, convert and strip EXIF/GPS from hundreds of images at once — entirely inside your browser.

### [Use it now: p32929.github.io/shrinkkit](https://p32929.github.io/shrinkkit/)

No signup. No server. No upload. Works offline after the first load.

## Why

Squoosh does one image at a time. TinyPNG uploads your files to somebody else's server and charges a subscription for bulk. ShrinkKit does the whole folder at once, on your own machine, and never sends a byte anywhere.

## What it does

1. Drop a whole folder of images → get them back compressed, as individual files or one ZIP
2. WebP / JPEG / PNG output, or keep the original format
3. Quality slider, optional max width/height resize
4. **Inspect metadata before you share** — one click reads the EXIF block out of every file in your browser and shows camera make/model, lens, body serial number, owner name, editing software, original timestamp and **GPS latitude/longitude with a map link**. Also reports XMP blocks and PNG text chunks. Free and unlimited.
5. **Strips EXIF and GPS metadata** — canvas re-encoding drops every metadata block, so location data in your photos never leaves with them
6. Never returns a file bigger than the one you gave it
7. One HTML file. No build step, no framework, no tracking, no analytics.
8. **Installable PWA** — install it from the browser and it keeps working with no network at all, because there is no server to talk to

## Free vs Pro

The free version compresses **20 images per batch** — enough to try it properly.

**[ShrinkKit Pro](https://p32929.gumroad.com/l/shrinkkit)** — one payment, no subscription:
1. Unlimited images per batch
2. Batch rename patterns: `{name}` `{n}` `{w}x{h}`
3. Settings remembered between visits

Building something in this space and want to skip writing your own compressor? **[White-Label Source License — $1,499](https://p32929.gumroad.com/l/shrinkkit)**: full source, rebrand it under your own name, resell it as your own product.

## Self-host it

It's one static file. Clone and open `index.html`, or drop it on any static host.

## Also free, from the same shelf

[Blackline](https://p32929.github.io/blackline/) — black out text in a PDF so it is actually removed, not covered. Also entirely in your browser, nothing uploaded. Its [redaction guides](https://p32929.github.io/blackline/guides/) cover metadata removal too, which is the other half of what stripping EXIF is for.

## Licence

Source-available — see [LICENSE](LICENSE). Read every line before you trust it with your photos, which is rather the point. Free to use and self-host; a paid licence is required to redistribute, resell or rebrand it.

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make ShrinkKit better.

## You might also like

<p><a href="https://openstore.pfay.workers.dev/cards/p32929/0?n=4&amp;repo=shrinkkit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=shrinkkit&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=shrinkkit&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (1)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/1?n=4&amp;repo=shrinkkit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=shrinkkit&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=shrinkkit&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (2)"></picture></a><br><a href="https://openstore.pfay.workers.dev/cards/p32929/2?n=4&amp;repo=shrinkkit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=shrinkkit&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=shrinkkit&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (3)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/3?n=4&amp;repo=shrinkkit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=shrinkkit&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=shrinkkit&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (4)"></picture></a></p>

<p><a href="https://p32929.github.io/share/?repo=shrinkkit"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
