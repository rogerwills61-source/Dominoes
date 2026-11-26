# Dominoes (v1.0.0)

An installable, zero-subscription **Dominoes** Progressive Web App (PWA) for mobile and desktop with near-real-time multi-device online sync, six classic variants, 4-player 2v2 partnerships, offline Pass-and-Play privacy curtains, and local Computer Bots (**DominoBot**).

## Features

- **Six Classic Double-6 Variants (2–4 Players):**
  - **Draw Dominoes:** Classic 2-end chain; draw from the visible boneyard until playable.
  - **Block Dominoes:** Pure strategy 2-end chain with no drawing.
  - **All Fives (Muggins):** Free 4-arm spinner on the first double; score open-end totals in multiples of 5 during play plus round-end pip tally rounded to the nearest 5.
  - **Fives & Threes (British Pub Classic):** 2-end chain scoring 1 point per 3 and 1 point per 5 on exposed open ends (e.g., 15 scores 8 points), with 61 / 121 pub targets.
  - **Maltese Cross:** Opening double acts as an immediate free 4-arm cross spinner (North, South, East, West).
  - **Mexican Train (Double-6 Edition):** Central engine hub stepping down from Double-6 to Double-0, personal radiating trains, shared Mexican Train, glowing open train markers, and double-satisfaction rules.
- **Flexible Tables:** Individual play or **4-Player Partnerships (2v2)** with any mix of human players across linked devices and Computer Bots (`Casual` / `Pro`).
- **Near-Real-Time Multi-Device Online Sync:** Zero backend required (`BroadcastChannel` + parallel 3-broker WSS MQTT + DTLS WebRTC DataChannels), 4-character Room Code, built-in ISO QR code & camera QR scanner, strict empty-seat locking, and clean disconnect handling.
- **Top-Down 60 FPS Table:** Crisp 3D-style bevelled tiles, optional **Coloured Pips**, face-down opponent racks at table edges, visible spare tile boneyard with live count, pan & pinch-to-zoom, **Tap-to-Place** ghost previews and **Touch-Drag** controls, plus **Sort Hand**.
- **Built-In Rules & Dockable Scorecard:** Automatic first-time "How to Play" cards per device/variant, 1-tap dockable Scorecard with timed cancellable score pauses, hidden-info-safe Undo (locked after boneyard draws), Web Audio tile clacks & haptics, and customizable **Appearance** themes.

## Deploy on GitHub Pages

1. Create a new GitHub repository (e.g., `dominoes`).
2. Upload the contents of this package (`index.html`, `manifest.json`, `sw.js`, `README.md`, and `icons/`).
3. Go to **Settings → Pages**, choose **Deploy from a branch** (`main` / `/ (root)`), and save.
4. Open your GitHub Pages URL on phone or desktop and tap **Menu → Install App** to install as a standalone offline-capable app.
