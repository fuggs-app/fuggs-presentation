# CLAUDE.md

This is a single-file Reveal.js presentation (`index.html`) for Fuggs.

## Key facts

- **No build step** – all dependencies loaded via CDN (Reveal.js 5.1, IBM Plex Sans)
- **Fuggs CI colors** defined as CSS custom properties at the top of `<style>` (orange `#FF521D`, etc.)
- **Language**: German (`lang="de"`)
- Slides use a `.slide-inner` wrapper div for consistent padding; the orange accent bar at the bottom is a `::after` pseudo-element on `.slide-inner`

## Editing slides

Add or edit `<section>` elements inside `.slides`. Each slide should contain a `<div class="slide-inner">`.
