<div align="center">

# Dhairya Kumar — portfolio

**I ship products, not just repos.**

A hand-coded, single-file portfolio with a custom Three.js shader blob, a Dynamic Island demo, and a built-in AI assistant that answers questions about me.

[![Live](https://img.shields.io/badge/Live-dhairya--portfolio.pages.dev-FF4A11?style=for-the-badge&logo=cloudflare&logoColor=white)](https://dhairya-portfolio.pages.dev)
[![No build step](https://img.shields.io/badge/Build_step-none-6C5CFF?style=for-the-badge)](#)
[![One file](https://img.shields.io/badge/Source-1_HTML_file-2ea44f?style=for-the-badge)](index.html)

</div>

---

## What's in here

No framework. No bundler. No `node_modules`. One `index.html`, a few images, and about 1,200 lines of hand-written HTML/CSS/JS that does more than most React sites.

| | |
|---|---|
| 🫧 **Iridescent blob** | A custom GLSL shader (simplex noise vertex displacement + fresnel iridescence) on an icosahedron. It morphs, drifts between sections as you scroll, swirls when you drag it, and pulses when you click it. No 3D model downloaded — it's pure math. |
| 🤖 **AXiS-mini chat** | A self-contained assistant that knows my whole background. Intent-matching engine with ~30 topics, rotating replies, and a contact CTA that appears on request. Zero backend, zero API keys, zero cost. |
| 🕹️ **Dynamic Island demo** | A live mini-mock of [AXiS](https://github.com/dhairyakumar018/AXiS), my desktop AI — hover it and it expands into the listening state, exactly like the real app. |
| 🎨 **Light + dark** | Full theming via CSS variables, respects `prefers-color-scheme`, remembers your pick. The 3D scene relights itself to match. |
| ♿ **Accessible** | Keyboard nav, focus traps in modals, ARIA labels, skip link, and a full `prefers-reduced-motion` path that freezes the animation. |

## Stack

`HTML` · `CSS` · `Vanilla JS` · `Three.js (r147)` · `Cloudflare Pages`

Fonts: Clash Display + Satoshi (Fontshare), JetBrains Mono (Google Fonts).

## Run it

```bash
# it's a static file — any server works
npx http-server . -p 5500
# → http://localhost:5500
```

## Deploy

```bash
npx wrangler pages deploy . --project-name=dhairya-portfolio --branch=main
```

## Featured work

| Project | What it does | Status |
|---|---|---|
| [LaunchFolio](https://launchfolio.tech) | AI resume & portfolio builder — form in, hosted site + PDF out | 🟢 Live |
| [Community Hero](https://community-hero-1014571245061.asia-southeast1.run.app/) | AI civic platform that routes local issue reports to the right municipal desk | 🟢 Live |
| [AXiS](https://github.com/dhairyakumar018/AXiS) | Desktop AI in a floating Dynamic Island — voice, memory, system control | 🧭 Main quest |
| [VisionTrack](https://github.com/dhairyakumar018/CodeAlpha_VisionTrack) | YOLOv8 + Deep SORT real-time object tracking | ✅ Shipped |
| [LexiFlux](https://github.com/dhairyakumar018/CodeAlpha_Language_Translation_Tool) | AI translation suite with native-accent TTS | ✅ Shipped |
| Fire Detection System | Arduino + IR flame sensors, ~95% accuracy | ✅ Built |

## Reach me

[![Email](https://img.shields.io/badge/Email-gdhairya29-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:gdhairya29@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhairya--kumar-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhairya-kumar-a77b2b35b)
[![GitHub](https://img.shields.io/badge/GitHub-dhairyakumar018-181717?style=flat&logo=github&logoColor=white)](https://github.com/dhairyakumar018)

<sub>Built by hand — one file, Three.js, and too much coffee.</sub>
