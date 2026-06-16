<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,40:7C3AED,100:A855F7&height=200&section=header&text=Riviera&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38" />

<a href="https://github.com/harshkawatra11/tourist-agency">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3400&pause=900&color=A855F7&center=true&vCenter=true&width=760&height=50&lines=The+Art+of+Going.;A+premium%2C+cinematic+tourism+landing+page;Scroll-jacked+3D+arcs+%C2%B7+GSAP+%C2%B7+Framer+Motion;Buttery+smooth+scrolling+with+Lenis" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Next.js%2014-1E1B4B?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React%2018-4F46E5?style=for-the-badge&logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-6D28D9?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-7C3AED?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/GSAP%20·%20ScrollTrigger-A855F7?style=for-the-badge&logo=greensock&logoColor=white" />
<img src="https://img.shields.io/badge/Framer%20Motion-5B21B6?style=for-the-badge&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/Lenis-1E1B4B?style=for-the-badge" />

</div>

---

<div align="center">

**A premium, cinematic tourism landing page — scroll-jacked 3D destination arcs, per-word reveals, count-up stats, and parallax storytelling, built on Next.js 14 and ported from an original `index.html` design reference.**

</div>

---

## <img src="https://img.shields.io/badge/-Tech%20Stack-1E1B4B?style=flat-square" height="22"/> &nbsp; Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind&theme=dark" />

</div>

- **Next.js 14** (App Router, TypeScript)
- **Tailwind CSS** for layout & design tokens
- **Framer Motion** for component-level animation
- **GSAP + ScrollTrigger** for scroll-jacked sections (the Destinations arc)
- **Lenis** for buttery smooth scrolling

---

## <img src="https://img.shields.io/badge/-Sections-1E1B4B?style=flat-square" height="22"/> &nbsp; Page Sections

| # | Section | Highlight |
| :--: | :--- | :--- |
| 1 | **Hero** | Cinematic Anton mega-word + italic accents (Borobudur / Tegallalang / Raja Ampat) |
| 2 | **Narrative** | Radial-glow centred quote with per-word reveal |
| 3 | **Destinations** | Sticky 3D arc fan, scroll-jacked via GSAP ScrollTrigger |
| 4 | **Film** | Mega cinema word + masked subject + region tabs |
| 5 | **Gallery** | 3D arc carousel |
| 6 | **Experiences** | Bento layout with hover scale + reveal stagger |
| 7 | **Stats** | Count-up on enter |
| 8 | **Testimonial** | Parallax background, glass card, slider |
| 9 | **Stories** | Three-card journal grid |
| 10 | **CTA + Footer** | Parallax invitation |

---

<details>
<summary><b>🚀 Getting Started</b></summary>

<br/>

```bash
cd riviera-next
npm install
npm run dev
```

Then open <http://127.0.0.1:3000>.

```
app/        layout.tsx (fonts, metadata) · page.tsx (assembly) · globals.css (tokens, cursor, grain)
components/ ui/ (Cursor, Nav, SideDock, ProgressRail) · sections/ (one file per section)
lib/        data.ts (destinations, gallery, testimonials, stories)
```

</details>

---

## <img src="https://img.shields.io/badge/-Notes-1E1B4B?style=flat-square" height="22"/> &nbsp; Notes

- The original `index.html` at the repo root is preserved as the design reference.
- The custom cursor is desktop-only (auto-disabled on touch).
- Animations respect `prefers-reduced-motion`.

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A855F7,50:7C3AED,100:4F46E5&height=120&section=footer" />
</div>
