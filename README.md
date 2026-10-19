# Gravity of Joy

A kinetic, mobile-first web experiment that turns positive thoughts into something you can feel. Joys drop into a virtual jar as emoji “marbles,” then tumble and roll as you tilt your phone.

This project is part of **[#BuildForJoy](https://buildforjoy.dev/)** — a non-commercial exploration of building for curiosity, play, and learning. Every feature is free and unlocked. There are no payments, subscriptions, or paywalls.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

---

## Why I Built This

I wanted to explore how **real-world motion** and a lightweight **2D physics engine** could make a simple idea feel tangible on a phone — no install, no backend, just HTML and sensors.

Along the way I learned:

- How the **Device Orientation** and **Device Motion** APIs behave across browsers (especially iOS permission flows).
- How to give emojis weight, bounce, and friction with **Matter.js** without a heavy game framework.
- That a small, self-contained page can still deliver a strong “physical” interaction loop: add → tilt → shake to clear.

---

## Features (all free)

- **Physical presence** — Matter.js gives emojis weight, bounce, and friction.
- **Motion interaction** — tilt your phone; joys roll with gravity.
- **Shake to clear** — a firm shake scatters and resets the jar.
- **Haptic feedback** — short vibrations on add/reset where the device allows it.
- **No install** — open it in a mobile browser (works well on GitHub Pages).

---

## Try it

1. Open `index.html` on a phone (or host it via GitHub Pages).
2. Tap **Enter Space** and allow motion/orientation access if prompted.
3. Tap **Add a Joy**, tilt to play, shake to clear.

**Desktop note:** motion sensors are phone-oriented; on desktop you can still add joys, but tilt/shake need a device with orientation APIs.

---

## Run locally

This is a static page — no build step, no package install, no payment SDKs.

```bash
# From the repo root, serve the folder with any static server, e.g.:
npx --yes serve .
# Then open the printed URL on your phone (same network) or locally in a browser.
```

Or simply open `index.html` directly. For Device Orientation permissions on some browsers, HTTPS (or localhost) is required.

---

## Built with

- **HTML5 / CSS3** — layout and UI
- **JavaScript (ES6)** — sensors and interaction
- **[Matter.js](https://brm.io/matter-js/)** — 2D physics
- Optional hosting via **GitHub Pages**

---

## License & disclaimer

Licensed under the [MIT License](./LICENSE).

This app is a non-commercial hobby experiment provided **AS IS** without warranty of any kind, express or implied. Use at your own risk.

Built for fun and curiosity as part of [#BuildForJoy](https://buildforjoy.dev/).
