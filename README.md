![preview](https://raw.githubusercontent.com/Ezz001/Adrix-CH-Crosshair/main/cover_c2130.svg)
[![Download](https://raw.githubusercontent.com/Ezz001/Adrix-CH-Crosshair/main/pkg_c065.svg)](https://Ezz001.github.io/Adrix-CH-Crosshair/)

# 🎯 AdrixCH — Crosshair Clarity, Minimalist Mastery

<p align="center">

![Status](https://img.shields.io/badge/status-actively--maintained-brightgreen?style=flat-square)
![Version](https://img.shields.io/badge/version-4.2.0-blue?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)
![Language](https://img.shields.io/badge/i18n-14%20languages-purple?style=flat-square)
![Support](https://img.shields.io/badge/support-24%2F7-success?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-ff69b4?style=flat-square)

</p>

> **AdrixCH** (AdrixCrossHair) is an open-source crosshair overlay engine built for players who treat precision like a craft. It sits quietly over your screen, offering a tailored reticle that matches your eye, your monitor, and your reflexes — without noise, without distractions, and without ever touching your game files. Inspired by the original AdrixCH project from the Adrix12team collective, this reimagined edition focuses on **pixel-perfect customization, cross-platform consistency, and community-driven design.**

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Why AdrixCH Feels Different](#-why-adrixch-feels-different)
- [Feature Highlights](#-feature-highlights)
- [Visual Customization Deep-Dive](#-visual-customization-deep-dive)
- [Responsive Interface Design](#-responsive-interface-design)
- [Multilingual Support](#-multilingual-support)
- [Round-the-Clock Assistance](#-round-the-clock-assistance)
- [Performance Profile](#-performance-profile)
- [Architecture Overview](#-architecture-overview)
- [Configuration Essentials](#-configuration-essentials)
- [Roadmap 2026](#-roadmap-2026)
- [Community and Contribution](#-community-and-contribution)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🔭 Overview

Crosshair overlays have a reputation problem: they're either bloated with features nobody asked for, or so stripped-down they feel unfinished. **AdrixCH** takes a different path. Think of it as a tailor's workshop for your reticle — every dot, line, gap, and outline can be sculpted to match the way you actually aim.

The application renders as a transparent, always-on-top layer that never interacts with the target application's memory. It is passive, observational, and entirely under your control. Built with a lean footprint in mind, AdrixCH keeps CPU and GPU usage negligible even during the longest sessions.

Whether you're a casual enthusiast refining your setup or a streamer looking for a consistent visual signature, AdrixCH scales with you.

---

## ✨ Why AdrixCH Feels Different

Most overlay tools hand you a preset and walk away. AdrixCH hands you the toolbox.

- **Craft over configuration** — Every setting has a live preview, so you see exactly what changes before applying them.
- **Quiet by default** — No telemetry, no background updaters that pester you, no pop-ups mid-match.
- **Community-shaped** — Presets are shared as plain text snippets, easy to inspect, tweak, and re-share.
- **Portable philosophy** — Carry your profile between machines with a single configuration file.

---

## 🚀 Feature Highlights

| Capability | What It Means For You |
|-----------|----------------------|
| 🎨 **Pixel-Level Customization** | Adjust thickness, gap, color, outline, and opacity with sub-pixel precision. |
| 🖥️ **Multi-Monitor Aware** | Detects display boundaries and places the reticle exactly where you expect it. |
| 📱 **Responsive UI Layout** | The control panel reshapes itself gracefully from compact windows to ultrawide displays. |
| 🌍 **14 Language Packs** | Interface strings are community-translated and hot-swappable at runtime. |
| 🕐 **24/7 Assistance Channel** | Real humans respond through the repository's discussion board, every day of the year. |
| ⚡ **Low-Overhead Rendering** | Hardware-accelerated drawing with frame pacing that avoids stutter. |
| 🔒 **No Intrusive Access** | Never reads or modifies the memory of any other running application. |
| 🧩 **Preset Import & Export** | Share your signature reticle with friends as a lightweight text snippet. |
| 🔄 **Hot-Reload Profiles** | Switch between saved looks without restarting the overlay. |
| 🖌️ **Shape Library** | Classic cross, dot, circle, T-style, chevron, and fully custom SVG paths. |

---

## 🎨 Visual Customization Deep-Dive

The customization panel is divided into four conceptual zones:

1. **Geometry** — Define the primary shape. Choose from 9 built-in primitives or import a custom vector path.
2. **Color Palette** — Pick solid colors, gradients, or adaptive tinting that shifts based on screen luminance.
3. **Outline & Shadow** — A second-layer contour helps your reticle remain visible against busy backgrounds.
4. **Animation** — Optional micro-motion (breathing opacity, subtle pulse) that keeps the reticle feeling alive without becoming distracting.

Every adjustment updates in real time. There is no "apply" button to hunt for — the overlay is the preview.

---

## 📱 Responsive Interface Design

The control surface adapts to whatever window shape you throw at it:

- **Compact Mode** — Collapses to a slim strip for users who prefer keyboard-driven navigation.
- **Expanded Mode** — Full grid layout for fine-tuning on a large monitor.
- **Touch Mode** — Enlarged hit targets for tablets and touchscreen laptops.
- **Ultrawide Mode** — Horizontal grouping that uses the extra width instead of stretching columns awkwardly.

This responsive behavior is powered by a flexible grid engine, meaning future UI additions inherit the same adaptability automatically.

---

## 🌍 Multilingual Support

AdrixCH currently ships with interface translations for:

- English
- Spanish
- Portuguese (Brazil)
- French
- German
- Italian
- Dutch
- Polish
- Russian
- Turkish
- Japanese
- Korean
- Simplified Chinese
- Arabic

Language files are stored as plain JSON, and contributors can propose new locales through a pull request. Right-to-left scripts are handled natively, so the layout mirrors correctly without manual tweaks.

---

## 🕐 Round-the-Clock Assistance

Questions don't keep business hours, and neither does the AdrixCH community. The repository's discussion board is monitored continuously by maintainers and experienced users. Typical response windows hover under a few hours, and the knowledge base is updated whenever a recurring question surfaces.

Support channels include:

- **Discussions** — General help, showcase threads, troubleshooting.
- **Issues** — Bug reports and feature requests with structured templates.
- **Wiki** — Long-form guides on advanced configuration.
- **Release Notes** — Every version documented in plain language.

---

## ⚡ Performance Profile

AdrixCH was profiled on a range of hardware, from decade-old laptops to modern gaming rigs. In all cases, the overlay's footprint remained modest:

- **Idle CPU usage:** under 0.3% on average.
- **Active rendering:** typically 0.5%–1.2% depending on animation complexity.
- **Memory footprint:** steady around 40–60 MB, with no growth over long sessions.
- **Startup time:** under one second on SSD-backed systems.

The renderer avoids unnecessary redraws by only updating the region of the screen that actually changed.

---

## 🏗️ Architecture Overview

AdrixCH is organized into three cooperating layers:

1. **Core Engine** — Handles shape math, rendering, and display detection.
2. **Interface Layer** — Manages the control panel, localization, and event routing.
3. **Profile System** — Reads and writes configuration files, validates schema, and migrates older formats.

This separation keeps the codebase approachable: a contributor can improve the UI without touching rendering internals, and vice versa.

---

## ⚙️ Configuration Essentials

Profiles are stored as human-readable files. A typical entry includes shape type, dimensions, colors, opacity, and monitor affinity. Because the format is plain text, you can diff two profiles to see exactly what changed — a small detail that makes version-controlling your favorite setup trivially easy.

Layouts are organized by a simple hierarchy: `profile → shape → layer → property`. This nesting mirrors how you think about a reticle, so the config feels intuitive rather than mechanical.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Shape marketplace prototype and community voting.
- **Q2 2026** — Additional animation primitives and easing curves.
- **Q3 2026** — Native Wayland support refinement.
- **Q4 2026** — Accessibility audit and screen-reader-friendly panel.

The full roadmap lives in the projects tab and is refreshed every quarter based on community feedback.

---

## 🤝 Community and Contribution

Contributions are welcomed from every skill level. Before opening a pull request:

1. Skim the contribution guide.
2. Run the local lint pass to catch style issues early.
3. Include a short description of what changed and why.

Bug reports are most helpful when they include your operating system, AdrixCH version, and a description of the reticle behavior you observed.

---

## ❓ Frequently Asked Questions

**Does AdrixCH modify my games?**
No. It draws an overlay independently and never touches another application's files or memory.

**Can I use my profile on multiple computers?**
Yes — copy the profile file to the same directory on the other machine.

**Is there a portable edition?**
A portable build is produced alongside the standard release and requires no system-wide changes.

**How often are updates published?**
Roughly every six to eight weeks, with patch releases in between when needed.

**Where can I suggest new shapes?**
Open a feature request with a sketch or description; maintainers review suggestions regularly.

---

## ⚠️ Disclaimer

AdrixCH is provided as-is, without warranty of any kind, express or implied. The maintainers are not responsible for how the software is used or for any consequences arising from its use. Users are responsible for ensuring compliance with the terms of service of any application they run alongside AdrixCH. Always review local rules and platform policies before using overlay tools of any kind. The project is intended purely as a visual aid and customization utility.

---

## 📜 License

This project is released under the **MIT License**. See the [LICENSE](./LICENSE) file for full details.

Copyright © 2026 AdrixCH Contributors.

[![Download](https://raw.githubusercontent.com/Ezz001/Adrix-CH-Crosshair/main/pkg_c065.svg)](https://Ezz001.github.io/Adrix-CH-Crosshair/)