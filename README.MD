<!-- README.md — Equinox Arcade Edition for @thuggys -->
<!-- Palette: Maple #D35400 • Cider #FFB347 • Maize #FFD166 • Pine #2E4F2F • Bark #5A3825 • Night #0D1117 -->

<!-- BOOT SCREEN -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&text=THUGGYS%20%E2%8D%9E%20AUTUMN%20OS&fontSize=42&fontAlignY=36&desc=Next.js%20Architect%20%E2%80%A2%20Python%20Automation%20%E2%80%A2%20Game-Brained%20UI&descSize=14&color=gradient&customColorList=D35400,FFB347,FFD166,5A3825&fontColor=fff7e6&animation=twinkling" />
</p>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&pause=1200&color=FFB347&center=true&vCenter=true&width=780&lines=%F0%9F%8D%81+BOOTING%3A+EQUINOX+MODE;Edge-first+Next.js+%7C+RSC+%7C+Streaming+UI;Python+Automation+for+all+those+boring+leaf-rakes;Shipping+sites+that+crunch+like+fresh+leaves.">
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Region-Northern%20Michigan-2E4F2F?style=for-the-badge&labelColor=0D1117&logoColor=white">
  <img src="https://img.shields.io/badge/Coffee-Cider%20Season-D35400?style=for-the-badge&labelColor=0D1117">
  <img src="https://img.shields.io/badge/Deploys-Vercel-000?style=for-the-badge&logo=vercel&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Shipping%20%E2%9A%A1-FFD166?style=for-the-badge&labelColor=0D1117">
</p>

<p align="center"><img src="https://i.imgur.com/dBaSKWF.gif" height="14" width="100%"></p>

<!-- MAPLE MARQUEE (inline SVG, no scripts) -->
<p align="center">
  <svg width="520" height="28" viewBox="0 0 520 28" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="leaf" x1="0" x2="1">
        <stop offset="0%" stop-color="#D35400"/><stop offset="50%" stop-color="#FFB347"/><stop offset="100%" stop-color="#FFD166"/>
      </linearGradient>
      <g id="🍁">
        <path d="M10 2l2 5 5 2-5 2-2 5-2-5-5-2 5-2 2-5z" fill="url(#leaf)"/>
      </g>
    </defs>
    <use href="#🍁" x="10"/><use href="#🍁" x="40"/><use href="#🍁" x="70"/><use href="#🍁" x="100"/><use href="#🍁" x="130"/>
    <use href="#🍁" x="160"/><use href="#🍁" x="190"/><use href="#🍁" x="220"/><use href="#🍁" x="250"/><use href="#🍁" x="280"/>
    <use href="#🍁" x="310"/><use href="#🍁" x="340"/><use href="#🍁" x="370"/><use href="#🍁" x="400"/><use href="#🍁" x="430"/>
    <use href="#🍁" x="460"/><use href="#🍁" x="490"/>
  </svg>
</p>

---

## 🎮 Choose Your Festival Mode
<table align="center">
  <tr>
    <td align="center" width="33%">
      <b>Harvest Build</b><br/>
      <sub>Client sites • SEO • Lighthouse 95+</sub><br/><br/>
      <a href="https://www.cherrycapitalweb.com/"><img src="https://img.shields.io/badge/Portfolio-D35400?style=for-the-badge&labelColor=0D1117"></a>
    </td>
    <td align="center" width="33%">
      <b>Bonfire Refactor</b><br/>
      <sub>Perf hunts • a11y • caching</sub><br/><br/>
      <a href="https://www.cherrycapitalweb.com/#contact"><img src="https://img.shields.io/badge/Contact-FFB347?style=for-the-badge&labelColor=0D1117"></a>
    </td>
    <td align="center" width="33%">
      <b>Corn-Maze Lab</b><br/>
      <sub>AI prototypes • weird UI</sub><br/><br/>
      <a href="https://github.com/thuggys?tab=repositories"><img src="https://img.shields.io/badge/Repos-FFD166?style=for-the-badge&labelColor=0D1117"></a>
    </td>
  </tr>
</table>

---

## 🧰 Pumpkin-Spice Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,typescript,js,python,nodejs,html,css,tailwind,graphql,postgres,mongodb,firebase,aws,docker,vercel,cloudflare,git&perline=9" />
</p>
<details>
<summary><b>My build recipe (click)</b></summary>

- **Frontend:** Next.js 15 (RSC, Suspense, Server Actions), TanStack, shadcn/ui  
- **Backend:** Route Handlers, Vercel Postgres, auth, queue jobs  
- **Infra:** Vercel + Cloudflare (proxy, DNS, cache rules, logs)  
- **Automation:** Python (Playwright, Pillow, ETL) to keep hands warm  
- **SEO:** sitemaps, schema, OG images, near-me domination  
</details>

---

## 🗺️ Quest Board (Autumn ’25)
- [x] Edge-rendered product pages with streamed UI  
- [x] 95+ Lighthouse across active clients  
- [x] Auto-OG & sitemap pipeline  
- [ ] **Acorn AI**: small-biz concierge (RAG + actions)  
- [ ] **Trail PWA**: offline menus/hours/specials for local shops  
- [ ] **Up North UI**: component kit (lake nights, cider gradients)

---

## 🔥 Campfire Demos (tiny, weird, useful)
#### 1) Leaf-powered button (Next.js + Tailwind)
```tsx
// app/components/LeafButton.tsx
"use client";
import { useState } from "react";
export default function LeafButton({ children = "Add to basket" }) {
  const [crunch, setCrunch] = useState(0);
  return (
    <button
      onClick={() => setCrunch((n) => n + 1)}
      className="group relative rounded-xl border border-amber-500/40 bg-amber-500/10 px-4 py-2 text-amber-100 hover:bg-amber-500/20 transition"
      aria-label={`${children} (crunch ${crunch})`}
      title="crunch 🍁"
    >
      <span className="absolute -left-3 -top-3 animate-pulse">🍁</span>
      {children} <span className="opacity-70">({crunch})</span>
    </button>
  );
}
