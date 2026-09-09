# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- **Primary (confirmed):** Portfolio visitors — recruiters, hiring managers, and technical reviewers evaluating the creator's work. They arrive at the live site, form a judgment about engineering and design craft within seconds, and decide whether to play or read on.
- **Secondary (confirmed):** Arcade/roguelite players who arrive to actually play. The landing must hand them into the game without friction.

## Product Purpose

CHRONO//BREACH V2 is a browser-based, high-speed arena roguelite / arcade shooter. Players pilot an evolving ship through an unstable time breach, using movement, gunplay, phase-dashes, parries, and time-bending abilities to survive escalating enemy waves and large boss encounters. (Source: CHRONO_BREACH_AI_HANDOUT.md, treated as repository-derived fact as of 2026-08-15.)

## Positioning

A complete, polished game built without a game framework: rendering, input, combat, progression, audio, persistence, and responsive cross-input controls implemented with browser-native APIs in a single static HTML file. Backed by an optional offline-first cloud layer (TypeScript/Express/PostgreSQL) with conflict-aware saves, global leaderboards, and an audited admin CMS — the game stays fully playable offline. No comparable portfolio piece pairs a real arcade game with production-grade backend operations in one zero-build deploy.

## Operating Context

- Lives at https://chrono-breach-v2.vercel.app/ (static, zero-build; client concentrated in `index.html`, ~3,000 lines).
- The landing screen is the first viewport of the same single-page app that hosts the game.
- Optional cloud API on Render; the game and landing must not depend on API availability.
- Primary usage: someone opens the URL on desktop; mobile web traffic exists and must remain respectable.

## Capabilities and Constraints

- Landing must coexist with the existing game: it lives inside `index.html` alongside menus, HUD, and Canvas gameplay. Scope of the redesign is the landing/hero surface only; in-game UI remains the incumbent look.
- Controls and features are fixed product truth: five sectors (Outer Rim → Chronos Rift), endgame chain (Endless, Convergence, Paradox Sovereign, Eternal Breach, NG+), five ship evolutions, cloud saves/leaderboards, offline-first behavior.
- Technical constraints: no frontend build step; vanilla HTML/CSS/JS; Canvas 2D; Web Audio; localStorage.
- **Open (creator must supply):** name/role, project dates, live/repo links beyond the Vercel URL, measurable results, preferred media. Do not fabricate any of these.

## Brand Commitments

- Name: CHRONO//BREACH V2 (with the `//` glyph treatment in the wordmark).
- Handout tagline: "BEND TIME. BREAK LIMITS. SURVIVE THE BREACH."
- Genre identity: neon sci-fi. The incumbent look is neon sci-fi; a redesign may replace the visual world but the product's identity as a fast time-breach arcade shooter is binding.

## Evidence on Hand

- `CHRONO_BREACH_AI_HANDOUT.md` — comprehensive, dated fact sheet (features, architecture, claim rules). Treat as sole copy authority; its "honest wording" rules bind any landing copy: no invented metrics, users, awards, dates, or authorship claims.
- `README.md` — setup/deployment facts.
- No gameplay screenshots, video, testimonials, or measured results exist in the repo. The landing must not imply them.

## Product Principles

1. **Proof over promise.** The landing's job is to demonstrate engineering craft — precise, confident, factual. Every claim must be traceable to the handout.
2. **Into the breach fast.** A visitor who came to play reaches the game in one obvious action; portfolio depth never buries the play affordance.
3. **One artifact, two readers.** The same page must satisfy a recruiter scanning for signal and a player scanning for "Play".
4. **Zero-build discipline.** All craft is hand-written HTML/CSS/JS; no framework, no build step, no external asset pipeline.

## Accessibility & Inclusion

- Reduced-motion preference must be honored (the game already ships a reduced-motion setting; the landing should respect `prefers-reduced-motion`).
- Keyboard-operable landing actions; readable contrast on dark backgrounds.
