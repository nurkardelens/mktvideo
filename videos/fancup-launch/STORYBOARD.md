---
format: 1920x1080
message: "FanCup lets fans predict AI-simulated football matches live, with zero real-money risk."
arc: Mystery cold open → Reveal → Real-product proof (roster / live match / fairness) → CTA / brand close
audience: sports fans already living in the Chiliz / Web3 fan-token ecosystem
mode: collaborative
---

## Video direction

**Palette system (from `frame.md`, creative-mode preset remixed onto brand tokens):** `ink` = `#0B0B0D` (near-black), `cream` = `#FFFFFF`, `yellow` = `#00E5FF` (electric cyan, exact brand accent), `orange` = `#E8113C` (Chiliz red, exact brand accent), `green` = `#0098A9` (a darker cyan-family tint — the preset's single reserved closing-plate ground), `pink`/`pink-dark` = red-family tints (`#F46884` / `#F02F56`) for secondary red emphasis. **Ground override:** the preset's own doctrine defaults to a cream ground on nearly every frame; this video instead runs the **near-black `ink` ground on every frame** to match the brief's dark-theme identity, with `cream` flipped to the text/border role and the two accents used as pops. Frame 7 alone swaps to the reserved `green` (dark cyan) plate — still dark, just a distinct hue, which is exactly the "color shift reserved for the closer" the preset intends. Real product screenshots (frames 4–5) are natively dark-UI too, so they sit into the near-black ground without a seam.

**Motion grammar + reveal model:** long-tail `power3` settles everywhere — no bounce, no `back.out`/`elastic.out` overshoot anywhere in this video (this is a keynote, not a toy). Since the video is silent, every frame's reveals are paced to an **internal beat grid** in place of voiceover cues: each Scene still reveals only one new piece at a time, spread across the frame's full duration, never front-loaded in the first ~25%. Holds are real holds — once a frame's content has resolved, it reads still; the only sanctioned aliveness is subtle jitter (`sine-wave-loop`, low amplitude) on a settled hero element.

**Rhythm / held-frame allocation:** Frames 1–2 are near-wordless atmosphere (mystery has nothing to dump, so it is naturally sparse — this is intentional silence, not underbuilding). Frame 3 is the held climax read (wordmark + tagline, settles and holds for its back half). Frames 4–5 are proof beats built around one real screenshot each — held on the screenshot once it lands. Frame 6 is the one dense trio (three tiles, the named density exception). Frame 7 is the final held sign-off.

**Negative list:** no lazy breathing, no slow pan/push in any frame's back half, no bouncy overshoot, no floating decorative "AI" gradients/bokeh, no browser chrome/cursors on the real screenshots (they're used as flat bordered surface cards, not simulated browser windows), no fabricated stat or claim anywhere — frame 6's three claims are lifted verbatim from the product's own How-It-Works copy.

---

## Frame 1 — Cold open

- scene: Pure near-black void. A single point of electric-cyan light sits dead-center, almost imperceptible, and slowly intensifies — no text, no logo, silence as the visual itself.
- duration: 4s
- transition_in: cut
- status: animated
- src: compositions/frames/01-cold-open.html
- type: hook
- persuasion: Pain validation (curiosity as pain)
- beat: tension
- blueprint: compose
- sfx: riser
- asset_candidates:

Scene 1 (0.0–2.0s): near-black `ink` void; a single point of `yellow` (electric cyan) light sits dead-center at ~5% opacity, barely visible — Centered, ~2% of frame, no other elements. Continuous glow bloom (`ambient-glow-bloom`) begins: opacity crawls 0.05→0.3 on a slow linear-feeling ramp. No camera move.
Scene 2 (2.0–4.0s): the point keeps intensifying — glow blooms further (opacity 0.3→0.85, scale 1.0×→1.4×) via `ambient-glow-bloom`; once, late in the window, one faint low-amplitude concentric ring pulses outward from it (`center-outward-expansion`, single pulse, not repeating) to seed anticipation. Holds on the brightening point at the cut — no camera move, no text ever enters this frame.

narrativeRole: Establish mystery with zero information — the viewer leans in because nothing is explained yet.
keyMessage: Something is about to happen.

## Frame 2 — Escalation

- scene: The cyan point fractures into glitching shards of red and cyan light; fragments of letterforms flare in and out of legibility (a stray "F", a stray "P") without ever resolving — tempo accelerates, cuts get shorter.
- duration: 3s
- transition_in: cut
- status: animated
- src: compositions/frames/02-escalation.html
- type: hook
- persuasion: Pain validation (curiosity escalation)
- beat: tension → anticipation
- blueprint: compose
- sfx: glitch-2
- asset_candidates:

Adapt: borrows `depth-scatter-assemble`'s tumbling-shard vocabulary for the scatter half only — there is no reassemble/resolve here, that payoff is deliberately deferred to Frame 3.
Scene 1 (0.0–1.2s): the incoming cyan point SHATTERS on a hard cut into 5–6 glitching shards of `yellow`/`orange` light that scatter just off-center (`depth-scatter-assemble`, tumbling start) — centered core, asymmetric scatter, still on the `ink` ground.
Scene 2 (1.2–2.2s): shards accelerate and flicker faster, carrying a directional `motion-blur-streak` on the fastest ones; a stray fragment of a letterform ("F", then later "P") flashes for a single beat each via hard-cut flash word-swap (`discrete-text-sequence`) and is gone before it resolves — no hold on either fragment.
Scene 3 (2.2–3.0s): shards reverse and compress inward at rising velocity — a `cut-the-curve` seam that matches direction/speed directly into Frame 3's `zoom-through` transition, so the collision reads continuous across the cut.

narrativeRole: Compress the mystery to its breaking point right before the reveal.
keyMessage: It's about to resolve.

## Frame 3 — The reveal

- scene: The fractured light collides and ignites into the full FANCUP wordmark, dead-center, full Archivo Black uppercase lockup with a one-line tagline beneath in accent: "PREDICT THE MATCH. WATCH IT LIVE."
- duration: 4s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-reveal.html
- type: product_intro
- persuasion: Show-don't-tell proof (the name IS the payoff)
- beat: relief + confidence
- blueprint: logo-assemble-lockup (Adapt)
- sfx: impact-bass-1, sparkle, chime
- asset_candidates:

Adapt: Product_Intro variant — keep the signature move (elements assemble into a fixed, centered mark); the "assembling elements" are Frame 2's incoming shards rather than a ring/orbit system, and there is no continuous orbit or camera tilt — the mark is fixed and 2D throughout.
Scene 1 (0.0–1.0s): shards collide at center (continuing the `zoom-through` seam from Frame 2) and IGNITE into a bright flash that resolves into the FANCUP wordmark's negative-space silhouette, Archivo Black uppercase, dead-center on the `ink` ground — Centered, ~55% of frame.
Scene 2 (1.0–2.2s): the wordmark's glyphs SOLIDIFY from the flash into solid `cream` fill (glow-ignite settling on an envelope, `asr-keyword-glow`); a thin `yellow` accent rule stub draws on beneath it (`svg-path-draw`).
Scene 3 (2.2–4.0s): the tagline "PREDICT THE MATCH. WATCH IT LIVE." reveals beneath in two phrases, 0.6s apart, via per-word staggered reveal (`dynamic-content-sequencing`), the second phrase landing in `yellow`; settles to a held read for the remainder — only subtle jitter (`sine-wave-loop`, low amplitude) on the wordmark's glow, no breathing.

focal: (typographic — no image asset)

narrativeRole: Resolve the cold open's tension into the product identity — the thesis statement of the whole video.
keyMessage: FanCup — predict AI football, live.

## Frame 4 — Six nations, six playstyles

- scene: The real roster screenshot lands as hero art (Argentina, Spain, Portugal, Belgium, Scotland, South Africa — each with its own tactical identity and form line), with "SIX NATIONS. SIX PLAYSTYLES." set large over/beside it.
- duration: 4s
- transition_in: crossfade
- status: animated
- src: compositions/frames/04-six-nations.html
- type: feature_showcase
- persuasion: Value stacking
- beat: momentum
- blueprint: device-surface-showcase (Adapt)
- sfx: whoosh-short
- asset_candidates: assets/roster.png — real "National Teams" roster grid, six nation cards with fan-token ticker, tactics tag, and Last-10 W/D/L strip

Adapt: static-tour variant — one real screenshot as the hero surface (no multi-screen cycling, since there's a single state to show); camera stays static throughout, all motion is element-level.
Scene 1 (0.0–1.4s): on the `ink` ground, the mono kicker "CHILIZ NATIONS CUP · ROSTER" fades in top-left — asymmetric 70/30, chrome inset, nothing else on screen yet.
Scene 2 (1.4–2.6s): the real roster screenshot slides in from the right edge and settles as a `cream`-bordered flat surface card occupying the right ~65% of the frame (surface establish: edge slide-in + settle, `power3`, no bounce) — asymmetric 35/65, 3 depth layers (kicker background, card midground, flat border foreground).
Scene 3 (2.6–4.0s): "SIX NATIONS." lands large on the left third via per-word staggered reveal (`dynamic-content-sequencing`), then "SIX PLAYSTYLES." lands beneath it 0.5s later in `orange` — holds for the remainder; only subtle jitter keeps the roster card alive, no breathing.

focal: assets/roster.png
roles: roster.png = cutout (bordered surface card, right 65% of frame)

narrativeRole: Prove there's real breadth and depth here — this is a built roster, not a mockup.
keyMessage: Every nation plays differently.

## Frame 5 — AI plays, you predict

- scene: The real "GOAL" moment screenshot (live top-down pitch, "Argentina 0-1 Portugal," the GOAL banner + "PORTUGAL Scores!") lands as hero art with "AI PLAYS THE MATCH. YOU CALL IT." set large.
- duration: 4s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/05-ai-plays.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: excitement
- blueprint: device-surface-showcase (Adapt)
- sfx: impact-bass-2
- asset_candidates: assets/match-goal.png — real live-match screenshot at the moment of a goal, scoreboard + top-down pitch simulation + GOAL banner

Adapt: static-tour variant again — the real GOAL screenshot is the one-state hero surface; static camera, no cursor, no screen-cycling.
Scene 1 (0.0–1.2s): full-bleed `ink` ground; "AI PLAYS THE MATCH." fades in centered, upper third, Archivo Black uppercase.
Scene 2 (1.2–2.6s): the real match-goal screenshot scale-pops in beneath it as a `cream`-bordered flat surface card, centered, ~60% of frame (`spring-pop-entrance` on a smooth long-tail settle — no overshoot) — centered, 3 depth layers.
Scene 3 (2.6–4.0s): "YOU CALL IT." lands beneath the card in `yellow` on a single hard-cut beat (`discrete-text-sequence`) — holds for the remainder; only subtle jitter, no breathing.

focal: assets/match-goal.png
roles: match-goal.png = cutout (bordered surface card, centered)

narrativeRole: Prove the AI-simulated match is real and live, not a static odds board.
keyMessage: The match plays itself — you predict what happens.

## Frame 6 — Play-money, provably fair, multi-chain

- scene: Three cream-bordered tiles self-assemble in a staggered cascade on the near-black ground — "PLAY-MONEY. ZERO REAL-MONEY RISK." (cyan tile) / "PROVABLY FAIR — MAGICBLOCK VRF" (red tile) / "ONE ACCOUNT, TWO CHAINS" (cream tile) — holding as a trio.
- duration: 5s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/06-trust-triad.html
- type: feature_showcase
- persuasion: Risk reversal + Value stacking
- beat: trust → confidence
- blueprint: grid-card-assemble (Reproduce)
- sfx: pop
- asset_candidates:

Reproduce: Key_Feature grid variant — labeled tiles cascade one-by-one into a row, then hold near-static with a slow push-in.
Scene 1 (0.0–1.2s): on the `ink` ground, the mono kicker "HOW IT WORKS" fades in top-center; the three-tile region establishes empty.
Scene 2 (1.2–3.2s): three `cream`-bordered tiles self-ASSEMBLE left-to-right in a staggered cascade (~0.3s gap, `center-outward-expansion`, short-path directly into slot, no bounce): "PLAY-MONEY. ZERO REAL-MONEY RISK." (`yellow` fill) → "PROVABLY FAIR — MAGICBLOCK VRF" (`orange` fill) → "ONE ACCOUNT, TWO CHAINS" (`cream` fill, `ink` text) — centered row, 3-up.
Scene 3 (3.2–5.0s): the array resolves and holds near-static; one traveling-glow sweep (`ambient-glow-bloom`) passes once left-to-right across the three tiles and settles — no breathing, subtle jitter only for the remainder.

focal: (typographic tiles — no image asset)

narrativeRole: Land the three concrete trust facts that make this safe and credible to try — sourced directly from the product's own "How It Works" page, not invented claims.
keyMessage: No real money at risk, fair by design, works across chains.

## Frame 7 — Brand close

- scene: Ground swaps to the deep cyan closing plate; the FANCUP wordmark draws itself back in above "Season I is live." and the URL fancup.trenchroyale.com settles beneath as a mono CTA rail.
- duration: 6s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/07-brand-close.html
- type: cta
- persuasion: Risk reversal (free/easy framing) + Authority by association (Chiliz ecosystem)
- beat: triumph + inevitability
- blueprint: logo-assemble-lockup (Adapt)
- sfx: whoosh-cinematic, chime
- asset_candidates:

Adapt: Brand_Outro variant — the ground-swap itself replaces "elements clear the stage" (there's no feature-pill formation to disperse here); keep the signature move — the mark draws itself on and the wordmark completes the lockup.
Scene 1 (0.0–1.2s): hard ground-swap cut to the reserved `green` (dark cyan) closing plate — the frame empties onto this one distinct hue, the only frame in the video to use it.
Scene 2 (1.2–3.0s): the FANCUP wordmark DRAWS itself on stroke-by-stroke (`svg-path-draw`) in `cream`, centered — Centered, ~50% of frame.
Scene 3 (3.0–4.4s): "Season I is live." fades in beneath the wordmark (`discrete-text-sequence`) in `ink`-on-`green`.
Scene 4 (4.4–6.0s): the mono CTA rail "fancup.trenchroyale.com" settles beneath as a pill badge (`spring-pop-entrance`, smooth long-tail, no overshoot) and holds to the end — this frame's one true exit (fade to black); subtle jitter only on the wordmark's glow until then.

focal: (typographic — no image asset)

narrativeRole: Land on identity and the single next action — the one thing to remember and the one thing to do.
keyMessage: FanCup — Season I is live, go play it.
