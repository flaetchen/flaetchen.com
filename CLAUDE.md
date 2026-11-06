# flaetchen.com — Project Instructions

## Mission
Build a completely custom, high-end, animated agency website for flaetchen.com. It must be visually distinctive, technically excellent, memorable and clearly custom-built.

It must NOT look like a purchased theme, Framer/Webflow template, SaaS landing page, generic agency site or collection of trendy effects.

## Fixed Corporate Design
Typeface: **Outfit only**. Use multiple Outfit weights intentionally. Do not introduce another font without explicit approval.

Colors:
- black
- white
- neutral light grey
- grey tonalities
- accent: `#bcff03`

Do not introduce other accent colors.

## Existing flaetchen DNA to preserve
- Outfit typography
- strong weight contrast
- large editorial headlines
- black/white/grey visual world
- neon #bcff03
- fullscreen dark navigation
- generous negative space
- alternating light/dark scenes
- asymmetric compositions
- strong founder/personal presence
- portrait photography
- reduced navigation
- calm moments combined with spectacular moments

## Primary Creative References
1. https://preymaker.com/
2. https://ownitt.fr/

These are references only. Do not copy layouts, motion, wording, assets, typography or branding.

Learn from Preymaker:
- visual scale
- cinematic project presentation
- strong imagery
- restraint
- work-first storytelling
- pacing and art direction

Learn from Ownitt:
- agency attitude
- brand voice
- strong statements
- service communication
- project storytelling
- personality
- expressive but understandable structure

## Core Rule
Combine Preymaker's visual power and restraint with Ownitt's attitude and structure, then express everything through flaetchen's own CI.

## Design Principles
- one dominant idea per viewport
- projects are the visual heart
- scenes instead of generic stacked sections
- whitespace is intentional
- strong but mature motion
- no card-heavy layouts
- no icon grids
- no SaaS aesthetics
- no repetitive fade-up animations

## Motion
Motion must serve reveal, transition, hierarchy, continuity, focus, storytelling or feedback.

Avoid bounce, random scale effects, excessive parallax, constant movement and decorative animation.

## Projects
Avoid generic project grids as the main experience. Prefer oversized media, cinematic project moments, curated sequencing and project teaser → case study continuity.

## Services
Do not use feature cards or icon grids. Treat Branding, Digital Design, Development and Strategy as chapters tied to real work.

## Founder
flaetchen is not an anonymous studio. Sven Flaetchen should remain visibly present, editorially and intentionally.

## Fullscreen Menu
The fullscreen dark menu is approved. Do not replace it with a conventional desktop dropdown or sidebar.

## Logo
The logo may adapt between dark and light contexts. Keep it stable and elegant.

## Technology
Preferred:
- current stable Next.js
- React
- TypeScript
- App Router
- Server Components by default
- CSS Modules + CSS variables
- GSAP / ScrollTrigger only where needed
- Three.js / React Three Fiber only for approved signature moments

Do not introduce smooth scroll, custom cursor or WebGL by default.

## SEO / GEO
All meaningful content must exist in semantic HTML and be indexable without animation. Use strong internal linking, project/service pages, metadata and structured data where useful.

## Accessibility
Support keyboard navigation, focus-visible, semantic controls, reduced motion and accessible contrast.

## Performance
Prioritize LCP, CLS, INP, minimal JS, optimized media, lazy loading, dynamic imports and clean animation lifecycle.

## Decisions
Do not make new corporate-design decisions silently. If a new design decision is required, present options and wait for approval.

## Implementation Rule
Before implementing a major scene, define:
1. what the user sees
2. dominant element
3. motion
4. transition
5. mobile behavior
6. reduced-motion behavior
7. performance risk

Do not build the whole site before the first key scenes are approved.
