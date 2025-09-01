<!-- README.md — Equinox Arcade Edition for @thuggys -->
<!-- Palette: Maple #D35400 • Cider #FFB347 • Maize #FFD166 • Pine #2E4F2F • Bark #5A3825 • Night #0D1117 -->

<!-- BOOT SCREEN -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&text=THUGGYS%20%E2%8D%9E%20AUTUMN%20OS&fontSize=42&fontAlignY=36&desc=Next.js%20Architect%20%E2%80%A2%20Python%20Automation%20%E2%80%A2%20Game-Brained%20UI&descSize=14&color=gradient&customColorList=D35400,FFB347,FFD166,5A3825&fontColor=fff7e6&animation=twinkling" alt="Autumn OS Banner"/>
</p>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&pause=1200&color=FFB347&center=true&vCenter=true&width=780&lines=%F0%9F%8D%81+BOOTING%3A+EQUINOX+MODE;Edge-first+Next.js+%7C+RSC+%7C+Streaming+UI;Python+Automation+for+boring+leaf-rakes;Shipping+sites+that+crunch+like+fresh+leaves." alt="Typing intro">
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Region-Northern%20Michigan-2E4F2F?style=for-the-badge&labelColor=0D1117&logo=map&logoColor=white">
  <img src="https://img.shields.io/badge/Coffee-Cider%20Season-D35400?style=for-the-badge&labelColor=0D1117">
  <img src="https://img.shields.io/badge/Deploys-Vercel-000?style=for-the-badge&logo=vercel&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Shipping%20%E2%9A%A1-FFD166?style=for-the-badge&labelColor=0D1117">
</p>

<p align="center"><img src="https://i.imgur.com/dBaSKWF.gif" height="14" width="100%" alt="Divider"></p>

<!-- MAPLE MARQUEE (inline SVG, no scripts) -->
<p align="center">
  <svg width="560" height="28" viewBox="0 0 560 28" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Maple marquee">
    <defs>
      <linearGradient id="leaf" x1="0" x2="1">
        <stop offset="0%" stop-color="#D35400"/><stop offset="50%" stop-color="#FFB347"/><stop offset="100%" stop-color="#FFD166"/>
      </linearGradient>
      <g id="leafGlyph">
        <path d="M10 2l2 5 5 2-5 2-2 5-2-5-5-2 5-2 2-5z" fill="url(#leaf)"/>
      </g>
    </defs>
    <g>
      <use href="#leafGlyph" x="10"/><use href="#leafGlyph" x="45"/><use href="#leafGlyph" x="80"/><use href="#leafGlyph" x="115"/><use href="#leafGlyph" x="150"/>
      <use href="#leafGlyph" x="185"/><use href="#leafGlyph" x="220"/><use href="#leafGlyph" x="255"/><use href="#leafGlyph" x="290"/><use href="#leafGlyph" x="325"/>
      <use href="#leafGlyph" x="360"/><use href="#leafGlyph" x="395"/><use href="#leafGlyph" x="430"/><use href="#leafGlyph" x="465"/><use href="#leafGlyph" x="500"/><use href="#leafGlyph" x="535"/>
    </g>
  </svg>
</p>

---

## 🔭 TL;DR (Choose Your Festival Mode)

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
  <img src="https://skillicons.dev/icons?i=react,nextjs,typescript,js,python,nodejs,html,css,tailwind,graphql,postgres,mongodb,firebase,aws,docker,vercel,cloudflare,git&perline=9" alt="Skill icons"/>
</p>

<details>
  <summary><b>Build Recipe</b></summary>

- **Frontend:** Next.js 15 (RSC, Suspense, Server Actions), TanStack, shadcn/ui  
- **Backend:** Route Handlers, Vercel Postgres, auth, queue jobs  
- **Infra:** Vercel + Cloudflare (proxy, DNS, cache rules, logs)  
- **Automation:** Python (Playwright, Pillow, ETL)  
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

### 1) Leaf-powered button (Next.js + Tailwind)
```tsx
// app/components/LeafButton.tsx
"use client";
import { useState } from "react";

export default function LeafButton({ children = "Add to basket" }) {
  const [crunch, setCrunch] = useState(0);

  return (
    <button
      onClick={() => setCrunch((n) => n + 1)}
      className="group relative rounded-xl border border-amber-500/40 bg-gradient-to-br from-amber-500/10 via-amber-500/5 to-transparent px-4 py-2 text-amber-50 shadow-[0_0_0_1px_rgba(255,193,7,.08)_inset] backdrop-blur-sm transition 
                 hover:border-amber-400/60 hover:from-amber-500/20 hover:shadow-[0_10px_30px_-10px_rgba(255,193,7,.35)]"
      aria-label={`${children} (crunch ${crunch})`}
      title="crunch 🍁"
    >
      {/* floating leaf */}
      <span
        className="absolute -left-3 -top-3 select-none"
        aria-hidden="true"
      >
        <span className="inline-block animate-bounce">🍁</span>
      </span>

      {/* shine sweep */}
      <span
        className="pointer-events-none absolute inset-0 overflow-hidden rounded-xl"
        aria-hidden="true"
      >
        <span className="absolute -inset-y-8 -left-10 w-16 rotate-12 bg-white/15 blur-[6px] transition-all duration-500 group-hover:-left-6 group-active:duration-200" />
      </span>

      {/* label */}
      <span className="relative z-10 font-medium tracking-wide">
        {children} <span className="opacity-70">({crunch})</span>
      </span>

      {/* ember grid */}
      <span
        aria-hidden="true"
        className="pointer-events-none absolute inset-0 rounded-xl opacity-0 transition group-hover:opacity-100"
        style={{
          backgroundImage:
            "radial-gradient(circle at 10% 10%, rgba(255,214,102,.12) 0 8px, transparent 9px), radial-gradient(circle at 85% 70%, rgba(211,84,0,.10) 0 10px, transparent 11px)",
        }}
      />
    </button>
  );
}
