# `chrono-eigen-manifold` — Local Agent Notebook

## Purpose
Standalone zero-dependency WebGL2 volumetric spectroscope visualizing 4D inverse stereographic Hopf fibrations ($\pi: S^3 \to S^2$), $SO(4)$ isoclinic spinor rotations, and Calabi–Yau quintic metric perturbations, with an in-app trilingual (`EN` / `RU` / `MN`) HUD and expandable axiomatic codex.

## Dataflow
```
[User Pointer / Sliders (Ξ, Ψ, Ω, Λ) / Language Switch (EN | RU | MN)]
       │
       ├──► I18N Dictionary ──► Live DOM HUD & Ξ-Codex Overlay
       ├──► 2D Canvas       ──► Poincaré Recurrence Phase Portrait
       └──► WebGL2 Uniforms ──► 72-Step Volumetric Hopf Raymarcher Shader
```

## Traps
- Keep `index.html` 100% self-contained with zero external CSS/JS runtime dependencies so GitHub Pages loads instantaneously and never suffers from third-party CDN blocks.

## TODO
- [x] M1: Create standalone `index.html`, trilingual `README.md` (EN/RU/MN), and `AGENTS.md`.
- [x] M2: Create GitHub repository `ssoj13/chrono-eigen-manifold` and push `main`.
- [x] M3: Enable and verify GitHub Pages deployment.

## Changelog
- **2026-10-28**: Initial creation of `chrono-eigen-manifold` with WebGL2 4D Hopf fibration shader, Poincaré phase canvas, and EN/RU/MN in-app switcher.
