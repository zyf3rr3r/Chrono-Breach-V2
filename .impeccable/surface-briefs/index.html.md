# Surface brief — landing / hero (index.html `#menu`)

## Scope & mode

The first viewport of the single-page game — the launch/landing screen only. Persuade. In-game HUD, panels, and all other screens keep the incumbent look; shared classes (.btn, .glass) are not restyled globally.

## Audience, job, action, proof, constraints

- Portfolio visitors (recruiters, technical reviewers) must read engineering craft in seconds; players must reach the game in one obvious action.
- Proof: real feature counts and system names from CHRONO_BREACH_AI_HANDOUT.md (5 sectors, 6 bosses, 26 upgrades, 5 ship evolutions, 16 hangar modules, 8 shards); no invented metrics.
- Must keep every JS binding: btnPlay, btnEndless, btnNGPlus, btnMap, btnLb, btnHow, btnLoadout, btnShop, btnSettings, gearBtn, pilotTag/avInit, mCredits/mShards/mCores, landingBest/Sector/Operation/ProgressText/ProgressBar, feats container.
- Zero build; vanilla HTML/CSS/JS; reduced-motion respected.

## Chosen direction — The Chronograph Plate

The landing is a Swiss chronograph technical spec sheet: engraved linework on light chart paper, spec-table hairlines, signal-red seconds accent, steel-gray annotations. The ship's exploded diagram names real combat systems with leader lines. Seed key 913c96aa; won as IMPECCABLE'S PICK over the assigned Breach Survey (user locked model-pick).

## Memorable moment

The signal-red chronograph hand sweeps the plate on real time; hovering the CHRONO CORE callout dilates its sweep — the page itself is a timepiece you can bend.

## Direction contract

- THESIS: The landing is the factory spec sheet of a time-weapon, refusing the category default of a dark neon stage — paper, ink, and one red hand instead of glow.
- OWN-WORLD: Ivory plate #edeae2, ink #101418 linework, signal red #c8331f as the only accent, steel #8a9099 annotations; hairline rules, engraved caps (Big Shoulders), mono annotations (Fragment Mono), letterpress-style stamps.
- STORY: A visitor understands in seconds that this is a complete browser arena roguelite engineered like an instrument, believes the engineering is real because every readout is, and enters the breach via the stamped DEPLOY action.
- FIRST VIEWPORT: Marginalia header strip (plate no., live combat network, pilot strip right). Left column: directive kicker, enormous CHRONO//BREACH title block, tagline, one factual paragraph, red ENTER THE BREACH stamp button beside ENDLESS MODE, numbered secondary nav. Right column: exploded ship SVG with callout lines to real systems (primary array, phase dash, tactical, chrono core) over a hairline graticule, red seconds hand sweeping a small subdial. Bottom strip: CALIBRE DATA spec table (real counts) and feats rail.
- FORM: The Chronograph Plate, IMPECCABLE'S PICK of seed 913c96aa.
- FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance.

## Signature interaction

Chronograph seconds hand bound to real time; hovering the CHRONO CORE callout (or the wordmark) dilates the sweep to slow motion; ENTER THE BREACH hover snaps the hand to 12 and starts it. Static under prefers-reduced-motion.

## Unresolved decisions

None blocking. Creator facts (name, role, dates) remain open in PRODUCT.md and are not fabricated on the landing.
