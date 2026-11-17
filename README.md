# Mobile Barcode Scanner

A barcode scanner that runs in your phone's browser. Scan with the camera, keep a list, and export it.

**Open it:** https://abdulaleem-ctrl.github.io/Mobile-Barcode-Scanner/

## Features

- Live camera scanning for EAN-13, EAN-8, UPC-A, UPC-E, Code 128, Code 39, Code 93, ITF, Codabar, QR, Data Matrix, PDF417 and Aztec
- Scan from a photo, or type a code by hand
- Quantities, notes, undo for delete and clear
- Export to Excel (.xlsx), CSV, or copy to the clipboard; share straight from the phone where supported
- Works offline: everything, including the barcode reader, is inside `index.html`

The list is saved in the browser on the device you scan with. Export it to keep a copy elsewhere.

## Notes

- The live camera needs the page to be opened over `https://` (GitHub Pages provides this).
- Flashlight and zoom buttons appear only where the browser allows control of them (mostly Android Chrome).
- Barcode decoding uses [zxing-wasm](https://github.com/Sec-ant/zxing-wasm) (ZXing-C++, Apache-2.0), embedded in the page. Fonts: Barlow Semi Condensed and B612 Mono (SIL Open Font License).
