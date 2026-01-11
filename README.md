# Webnew (AayanShaikh.co)

Portfolio site built with Astro and Tailwind. Features interactive project popups with galleries, image preloading, full-size viewer, and staggered text/card animations.

## Features
- Project grid with popups (gallery + full-size viewer, ESC/overlay close).
- First image used as card cover; images preloaded/prefetched for snappier navigation.
- Subtle scrollbar styling and popup fade/scale animation.
- Staggered text fade-in across pages; staggered card entry on projects.
- Global layout components for desktop/mobile nav and footer with commit link.

## Getting Started
1) Install dependencies:
```bash
npm install
```
2) Run dev server:
```bash
npm run dev
```
3) Build for production:
```bash
npm run build
```
4) Preview production build:
```bash
npm run preview
```

## Project Notes
- Code lives under `src/` (pages, components, layouts, styles).
- Assets are served from `public/` (per-project folders for gallery images).
- CSS utilities/keyframes for popups and fade-in live in `src/styles/global.css`.
- Projects page scripts handle popups, viewer, ESC handling, image preload/prefetch, and cover swapping.
- Homepage preloads project cover images to speed up first visit to Projects.

## Tech
- Astro 5, Tailwind CSS 4, React support (where needed).
- Node 18+ recommended.

## Deployment
- Run `npm run build` and deploy the `dist/` output to your static host of choice.
