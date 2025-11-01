# Simple QR Free, Privacy-First, Donation-Supported

Generate QR codes locally in your browser. No tracking. No server. 100% client-side. I am so sick of searching for a simple QR code generator but all of them either have to many ads or just require signing up. 

Link1: [https://korawichkavee.github.io/simple-qr]

Link2: [qr.korawichmawinkavee.com]

## Features
- Text/URL → QR with custom size, margin, colors
- Error correction (L/M/Q/H)
- One-click PNG download and clipboard copy
- Shareable presets via URL params
- **PWA**: installable and works offline

## Privacy
All processing happens locally in your browser. Nothing is uploaded. (so I can run this without going backrupt on storage too lol) 

## Tech
- Vanilla HTML/CSS/JS
- [qrcodejs (MIT)](https://github.com/davidshimjs/qrcodejs)
- GitHub Pages hosting + PWA (manifest + service worker)

## Donate
If this helps, consider donating:
- PayPal: `https://paypal.me/KorawichKavee` [MyPayPal](https://paypal.me/KorawichKavee)

## Local dev
Just open `index.html` or run a local server:
```bash
python -m http.server 8000
# then visit http://localhost:8000
