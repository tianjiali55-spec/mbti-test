# 🧠 MBTI Personality Test

A beautifully designed MBTI (Myers-Briggs Type Indicator) test web app with camera interaction, gesture support, and stunning animations.

## Features

- **20 carefully crafted questions** covering all 4 MBTI dimensions (E/I, S/N, T/F, J/P)
- **Canvas particle background** with interactive mouse/touch following
- **Glassmorphism UI** with backdrop blur and smooth transitions
- **Live camera filters** — vivid, monochrome, warm tones
- **Photo capture** embedded in your result card
- **16 complete personality type descriptions** in Chinese
- **iPad-optimized** with touch gestures and responsive layout
- **Share support** via Web Share API

## Design Inspirations

Drawing from 10 design-forward projects: Stripe, Apple, Linear, Vercel, Figma, Notion, Arc, Raycast, Loom, GitHub.

## Run Locally

```bash
git clone https://github.com/<your-username>/mbti-test.git
cd mbti-test
python -m http.server 8080
```

Then open `http://localhost:8080` on desktop, or `http://<your-ip>:8080` on iPad.

## Tech Stack

- Vanilla HTML/CSS/JavaScript — no frameworks, no build step
- Canvas API for particle effects
- MediaDevices API (getUserMedia) for camera access
- Web Share API for sharing results
