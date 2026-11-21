# PocketScan

A phone document scanner and PDF tool that runs entirely in the browser. Nothing is uploaded anywhere.

**Open the app:** https://eman12211e.github.io/camerascan/

## What it does

- **Scan with your camera:** choose *Single page* (adjust corners and filter) or *Multiple pages* (snap page after page, each one is cropped and cleaned automatically).
- **Clean white filter:** paper comes out bright white with sharp text. Also Color boost, Grayscale, Black & white and Original.
- **Merge PDFs:** add PDFs and photos, drag pages to reorder across files, rotate or delete pages.
- **Sign:** draw or type your signature (saved on your device), drag and resize it on any page, add the date.
- **Send:** Share PDF opens the phone's share sheet (Messages, Discord, Mail…). *Share as images* is for Instagram, which doesn't take PDFs. Download works too.

## Files

| File | What it is |
|---|---|
| `index.html` | The app (~75 KB). Edit this one. Loads pdf-lib, pdf.js and SortableJS from a CDN, with backup CDNs. |
| `pocketscan.html` | Offline copy (~2 MB) with those libraries built in. Works without internet; not meant for editing. |

## Add it to your iPhone

1. Open the link above in **Safari**.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. The first time you tap Scan, allow camera access.

The live camera and the share button need the page to be opened from an `https://` address like the one above. Opening the file straight from the Files app won't allow them.

## Libraries

[pdf-lib](https://pdf-lib.js.org/) (MIT) · [pdf.js](https://mozilla.github.io/pdf.js/) (Apache-2.0) · [SortableJS](https://sortablejs.github.io/Sortable/) (MIT)
