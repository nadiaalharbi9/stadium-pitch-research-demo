# Al Jawhara Turf Twin

Independent, public portfolio prototype: an immersive Three.js stadium with pitch inspection and operations review.

[Open the live prototype](https://nadiaalharbi9.github.io/stadium-pitch-research-demo/)

## Source and deployment

This branch hosts the compiled static site for GitHub Pages (main / root). Download [source.zip](source.zip) for the complete modular source, package lock, tests, README and research documentation. Source commit: `3c899915ec16a28ece4def5c0c1e3def03cf3788`; development branch: `feature/immersive-stadium-simulator`. Extract it, run `npm ci`, then `npm run dev`. `npm run build` produces the static application.

This upload preserves compiled asset bytes and flattens the assets directory; only index.html asset references were adjusted. No backend or credentials are needed.

## Verification and boundaries

Production build and six domain tests passed. Seventeen desktop Chrome checks covered WebGL, camera controls, nine zone raycasts, persistence, review/export, responsive layout, and WebGL failure.

Architecture is an approximate Al Jawhara-inspired study, not official CAD/BIM. Initial observations are synthetic; edits stay in this browser. No live stadium connection, sensor measurements, safety certification or recovery prediction. Manrope is bundled under the included OFL license.
