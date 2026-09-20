# Aura Music Institute: cinematic 3D scroll site

Single-file site (index.html). No build step.

## Run it
- Open index.html in Chrome, Edge, Safari or Firefox (internet needed on first load for Three.js, GSAP, Lenis and Google Fonts).
- To host: upload index.html to any static host (Netlify, Vercel, GitHub Pages, your own server).

## Fill in your real details
Open index.html in a text editor and search for `CONFIG`. Edit:
- established, students, events (numbers count up automatically)
- address, phone, email, website
- whatsapp (digits with country code, e.g. 919876543210)
- instagram, youtube, facebook (full URLs)

Add real gallery photos in the `GALLERY` list: {cat:'Events', src:'https://…', alt:'Description'}.
Mentors, programs and events are the `MENTORS`, `PROGRAMS` and `EVENTS` lists just below CONFIG.

## Before going live
- Update the JSON-LD block in <head> (address, phone, email, url, sameAs) and add an og:image.
- Placeholders like [Year] and [Mentor name] are intentional: nothing is invented.
