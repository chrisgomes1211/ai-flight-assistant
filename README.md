# ✈️ AI Flight Assistant

An interactive, all-in-one airline chatbot — no backend, no frameworks, just a single HTML file. Built for SkyWing Airlines (fictional budget carrier).

## Features

| Feature | Description |
|---|---|
| **🎤 Voice Conversation** | Speech-to-text + text-to-speech with animated avatar |
| **📄 PDF Boarding Pass** | Client-generated with QR code (jsPDF + qrcode-generator) |
| **✈️ Live Flight Tracker** | Simulated live data with refresh, delays, weather, altitude |
| **🧳 Trip Overview** | Flight + hotel + activities in one card |
| **🛋️ SkyWing Lounge Pass** | Mock premium lounge access card |
| **🚗 Ride to Airport** | Grab/Uber mock booking with interactive "Book" buttons |
| **📖 Bangkok Guide** | Weather, currency, food, attractions, packing tips |
| **⏱️ Countdown Timer** | Live departure countdown in header |
| **💺 Interactive Seat Map** | Clickable 12-row cabin with real-time selection |
| **🎉 Confetti Bursts** | Celebrations on seat change, check-in, baggage add |
| **🧠 Gemini AI (optional)** | Paste your free Google AI Studio key → AI-powered chat |
| **🔄 Typewriter Effect** | Bot messages type out character by character |
| **🌗 Background Paper Planes** | Ambient floating animations |

## How to use

Open [`index.html`](index.html) in any browser. That's it.

### Enable AI (optional)

1. Go to [aistudio.google.com](https://aistudio.google.com) → "Get API key" (free, no credit card)
2. Tap the ⚙️ gear in the chatbot header
3. Paste your key → Save

## Tech stack

- **Zero frameworks** — vanilla HTML/CSS/JS
- **jsPDF** — PDF generation (loaded from CDN)
- **qrcode-generator** — QR codes for boarding pass (loaded from CDN)
- **Gemini 2.0 Flash-Lite** — optional AI via REST API
- **Web Speech API** — speech recognition + synthesis (built into browsers)

## Build

No build step. Edit `index.html`, refresh browser.

## Live demo

https://chrisgomes1211.github.io/ai-flight-assistant
