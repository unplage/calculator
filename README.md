# Calculator - 科学计算器 PWA

A scientific calculator PWA with dark theme, history tracking, and offline support.

## Features

- Basic arithmetic (`+`, `-`, `×`, `÷`)
- Scientific functions (`sin`, `cos`, `tan`, `ln`, `log`, `√`, `x²`, `xⁿ`, `n!`, `1/x`)
- Constants `π` and `e`
- Degree/Radian mode toggle
- Calculation history (persisted to localStorage)
- Keyboard input support
- Sound and haptic feedback
- Offline-ready via Service Worker
- Responsive layout (mobile, tablet, desktop)

## Usage

Serve locally:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a browser.

## PWA Installation

Open the app and use the browser's "Add to Home Screen" option. The app works offline after the first visit.

## Tech Stack

Single-file HTML + CSS + JS (no build tools), IndexedDB-ready Service Worker.
