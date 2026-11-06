# Technical Architecture

## Stack
- current stable Next.js
- React
- TypeScript strict
- App Router
- Server Components by default
- CSS Modules
- CSS Custom Properties
- GSAP / ScrollTrigger only where required
- optional Three.js / React Three Fiber for approved signature moments

## Project Root
Use `/web`.

Suggested structure:
```text
web/
└── src/
    ├── app/
    ├── components/
    │   ├── layout/
    │   ├── navigation/
    │   ├── projects/
    │   ├── services/
    │   ├── scenes/
    │   └── ui/
    ├── content/
    ├── motion/
    ├── lib/
    ├── styles/
    └── types/
```

## Server / Client Boundary
Default to Server Components. Use Client Components only for animation, browser APIs and stateful interaction.

## Styling
Use CSS Modules, global tokens and fluid `clamp()` scales.

## Motion Architecture
Do not build a motion framework before the approved prototype exists. Extract reusable patterns only after they repeat.

## Media
Use optimized responsive images and compressed, poster-backed video. Pause video outside viewport.

## 3D / WebGL
Do not include in the initial foundation. Add only for an approved use case.

## No Default Smooth Scroll
Start native.

## No Default Custom Cursor
Only add if an approved interaction needs it.

## Deployment
Assume a modern Node-capable deployment unless changed later.
