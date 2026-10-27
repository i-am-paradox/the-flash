<div align="center">

# ⚡ THE FLASH — CINEMATIC SCROLL EXPERIENCE

**A high-fidelity scroll-scrubbed web experience built with Next.js, GSAP ScrollTrigger, and Lenis.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework: Next.js 16](https://img.shields.io/badge/Next.js-16-000000?logo=next.js)](https://nextjs.org/)
[![Motion: GSAP](https://img.shields.io/badge/Motion-GSAP_3-88CE02?logo=greensock)](https://greensock.com/)
[![Smooth Scroll: Lenis](https://img.shields.io/badge/Scroll-Lenis-orange)](https://github.com/darkroomengineering/lenis)
[![Author: Paradox](https://img.shields.io/badge/Author-Paradox-blueviolet)](https://github.com/i-am-paradox)

</div>

---

## ⚡ Overview

**THE FLASH** is an open-source cinematic scrollytelling web experience crafted by **Paradox Studio**. Rather than streaming pre-baked video files, the site dynamically renders synchronized high-resolution image sequences directly to an HTML5 canvas governed by scroll momentum.

Every user gesture maps to frame-accurate playback, viewfinder HUD diagnostics, speed streaks, chromatic impact flashes, and interactive stacked breakdowns.

### 🌟 Key Highlights
- **Scroll-Scrubbed Canvas Engine**: 30FPS frame sequence playback synchronized directly to Lenis inertia scroll.
- **Viewfinder HUD & Chromatic Impacts**: Real-time reactive overlays that flare on high-speed deceleration and scene transitions.
- **Stacked Card Breakdown**: GSAP ScrollTrigger pinning and 3D receding transform depth.
- **Dynamic Flying Art Gallery**: Triple-lane asynchronous parallax art ribbon with direction alternation.
- **Full Accessibility & Reduced Motion Support**: Native fallback for visitors with vestibular sensitivities or `prefers-reduced-motion`.

---

## 🛠️ Architecture & Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Core Framework** | [Next.js 16](https://nextjs.org/) (App Router, Turbopack) | Server-side rendering, static optimization, and asset piping |
| **UI Library** | [React 19](https://react.dev/) | Component orchestration and state binding |
| **Motion & Scroll** | [GSAP 3](https://greensock.com/) + ScrollTrigger | High-performance timeline management and scrub mechanics |
| **Inertia Physics** | [Lenis](https://github.com/darkroomengineering/lenis) | Decoupled smooth scrolling physics |
| **Styling** | [TailwindCSS v4](https://tailwindcss.com/) | Low-overhead zero-runtime CSS tokens |
| **Language** | [TypeScript 5](https://www.typescriptlang.org/) | Strict type safety across components and animation stores |

---

## 🚀 Quickstart

### Prerequisites
- Node.js 20+ or [Bun](https://bun.sh/) installed

### Installation & Run

```bash
# 1. Clone the repository
git clone https://github.com/i-am-paradox/the-flash.git

# 2. Enter project directory
cd the-flash

# 3. Install dependencies
bun install
# or: npm install

# 4. Start local development server
bun dev
# or: npm run dev
```

Visit `http://localhost:3000` in your browser.

### Production Build

```bash
bun run build
bun run start
```

---

## ⚖️ Legal & Disclaimer

This is an independent non-commercial open-source fan tribute built by **Paradox Studio**. It is not affiliated with, endorsed by, or sponsored by Warner Bros., DC Comics, or DC Studios. All trademarks, character names, and related properties belong to their respective copyright holders.

---

<div align="center">

Crafted with ⚡ by [Paradox](https://github.com/i-am-paradox)

</div>
