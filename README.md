# Vistash — save-anything library prototype

This is a standalone static web app for saving links, images, videos, captions, and notes. It can be hosted as a separate website and installed as a PWA on supported browsers.

## Deploy

Upload the contents of this folder to a static host. The site must be served over HTTPS for PWA installation and the native share target. Keep `index.html`, `manifest.webmanifest`, and `icon.svg` together at the site root.

## Prototype boundaries

- Links can be saved from Pinterest, Cosmos, video platforms, and other websites. Page links are bookmarks; the prototype does not scrape pages or download their images/videos automatically.
- Image and video files selected from a device are stored in that browser's IndexedDB. They are not uploaded to a server.
- Captions can be pasted or imported from `.txt`, `.vtt`, or `.srt` files.
- Search and category suggestions run locally with simple keyword matching. There is no AI service connected.
- Library data is local to each browser. Sign-in, cloud sync, cross-device access, production transcription, and semantic AI answers require a backend and service credentials.
- The initial cards are clearly marked sample examples and do not point to real creator content.
