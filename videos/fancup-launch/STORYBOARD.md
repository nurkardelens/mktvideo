---
format: 1920x1080
message: "Something is colliding — join the FanCup waitlist before kickoff."
arc: Mystery cold open → Escalation → Reveal (logo, real tagline) → Extended mystery (no explainer) → Waitlist CTA close
audience: sports fans already living in the Chiliz / Web3 fan-token ecosystem
mode: collaborative
---

## Video direction

**Pivot note (supersedes the earlier "Season I is live" cut):** this is now a pre-launch waitlist
teaser, not a live-product demo. Per explicit user decision, real in-app gameplay/UI screenshots
(roster grid, live GOAL moment, How-It-Works trust facts) are OUT — showing them would imply the
product is already playable, contradicting "join the waitlist, kickoff is coming." The video stays
cryptic through the whole build and never resolves into an explainer; it resolves only into the
brand reveal and the waitlist ask.

**Palette system:** `ink` = `#0B0B0D` (near-black, the ground on every frame). The abstract mystery
beats (1, 2, 4, 5) run this video's own invented red/cyan brand shell — `yellow` = `#00E5FF`
(electric cyan) / `orange` = `#E8113C` (Chiliz red) from `frame.md`. The reveal (3) and waitlist
close (6) instead use the REAL fancup logo mark and copy verbatim from the actual waitlist page at
fancup.trenchroyale.com — a lime-green soccer-ball icon + lowercase "fancup" wordmark, the real
headline "Solana and Chiliz, on the same pitch." (gradient "Solana," red "Chiliz"), the real lime
subhead, and the real "Join the waitlist" CTA. A real asset keeps its real color rather than being
recolored into the shell — the same principle already used for the real screenshots earlier in
this project.

**Type:** the abstract beats use `frame.md`'s Archivo Black / JetBrains Mono. The reveal and close
use **Inter** (Bold/ExtraBold for the wordmark and headline, Medium/SemiBold for body) to match the
real site's rounded geometric sans — see `frame.md`'s "Font loading" section.

**Motion grammar + reveal model:** long-tail `power3` settles everywhere, no bounce/overshoot
anywhere. Silent video — reveals paced to an internal beat grid, never front-loaded. Holds are real
holds; subtle jitter (`sine-wave-loop`, low amplitude) is the only sanctioned aliveness on a
settled hero.

**Rhythm:** frames 1–2 are wordless atmosphere (unchanged from the prior cut). Frame 3 is the one
moment of clarity — the real logo + real tagline — but it does NOT explain the product, only names
it and quotes its own real headline. Frames 4–5 extend the mystery further with no clarifying
copy (confusion-marketing energy — a fan is meant to feel curiosity, not get a feature rundown).
Frame 6 is the held CTA close.

**Negative list:** no lazy breathing, no slow pan/push in any back half, no bouncy overshoot, no
floating decorative "AI" gradients, no real in-app UI screenshots anywhere in this cut, no
fabricated claims, no explaining what FanCup actually does beyond its own real tagline.

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

- scene: The fractured light collides and resolves into the real fancup mark — a lime-green soccer-ball icon beside the lowercase "fancup" wordmark, Inter ExtraBold, centered — with the site's own real headline beneath: "Solana and Chiliz, on the same pitch." (gradient "Solana," red "Chiliz").
- duration: 5s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-reveal.html
- type: product_intro
- persuasion: Show-don't-tell proof (the real name + real tagline IS the payoff — no invented product claim)
- beat: relief + confidence
- blueprint: logo-assemble-lockup (Adapt)
- sfx: impact-bass-1, sparkle, chime
- asset_candidates:

Adapt: Product_Intro variant — keep the signature move (elements assemble into a fixed, centered mark); the "assembling elements" are Frame 2's incoming shards rather than a ring/orbit system, and there is no continuous orbit or camera tilt — the mark is fixed throughout. Unlike the prior cut, the mark that resolves here is the REAL fancup logo (soccer-ball icon, real lime green, Inter wordmark) rather than an invented red/cyan Archivo Black lockup — the shard-collision energy is this video's own shell delivering the real brand asset intact.
Scene 1 (0.0–1.2s): shards collide at center (continuing the `zoom-through` seam from Frame 2) and IGNITE into a bright flash on the `ink` ground.
Scene 2 (1.2–2.4s): the flash resolves into the real fancup mark — the lime-green soccer-ball icon scale-pops in first (small, ~64px, to the left), then the lowercase "fancup" wordmark (Inter ExtraBold, white) cascades in beside it letter-by-letter — Centered, ~30% of frame, held small and clean (not oversized) exactly as the real asset reads.
Scene 3 (2.4–5.0s): beneath the mark, the real headline reveals in two per-word staggered waves (`dynamic-content-sequencing`): "Solana and" (white) → "Chiliz," (red `orange`) on the first line, then "on the same pitch." (white) on the second — held read for the remainder; only subtle jitter on the icon's glow, no breathing. No subhead, no CTA yet — this frame only names the collision, it does not explain or invite action (that's Frame 6).

focal: (typographic + a small inline SVG logo mark — no photographic asset)

narrativeRole: Resolve the cold open's tension into the real brand identity and its own real one-line thesis — nothing more explained yet.
keyMessage: fancup — Solana and Chiliz, on the same pitch.

## Frame 4 — Collision (extended mystery, no explainer)

- scene: Two abstract marks drift toward each other across the frame — a purple-to-teal gradient orb (echoing "Solana") and a red orb (echoing "Chiliz") — approaching but never fully merging, with fragments of text flickering in and out ("TWO WORLDS." / "ONE ARENA.") never settling into a full sentence.
- duration: 5s
- transition_in: crossfade
- status: animated
- src: compositions/frames/04-collision.html
- type: benefit_highlight
- persuasion: Curiosity gap (withholding, not revealing)
- beat: intrigue
- blueprint: compose
- sfx: whoosh-short
- asset_candidates:

Scene 1 (0.0–1.8s): on the `ink` ground, a purple-to-teal gradient orb drifts in from the left edge and a red orb (`orange`) drifts in from the right, both small (~120px), moving slowly toward center — Centered convergence, asymmetric entry.
Scene 2 (1.8–3.4s): as the orbs near the center (never touching — held ~200px apart at closest), the fragment "TWO WORLDS." flashes once in cream, holds 0.4s, then hard-cuts to blank (`discrete-text-sequence`, single flash, no full resolve) — a confusion-marketing beat that names a feeling, not a feature.
Scene 3 (3.4–5.0s): a second fragment "ONE ARENA." flashes the same way, slightly larger; the two orbs pulse once in sync (`ambient-glow-bloom`, a single shared bloom, not a merge) then settle to a held, mysterious stillness — no resolution, no explanation, only subtle jitter on both orbs.

focal: (abstract CSS/SVG orbs — no photographic asset)

narrativeRole: Extend the intrigue instead of explaining anything — a confusion-marketing beat that deepens curiosity rather than answering it.
keyMessage: Something is colliding. It isn't explained yet.

## Frame 5 — Kickoff tease

- scene: A faint circular arc (echoing the real waitlist page's stadium/orbit line) glows low in frame; glitching fragments of "KICKOFF IS COM—" flicker and cut before completing, never spelling the full word.
- duration: 5s
- transition_in: push-slide LEFT
- status: animated
- src: compositions/frames/05-kickoff-tease.html
- type: benefit_highlight
- persuasion: Scarcity/urgency (withheld completion)
- beat: anticipation → urgency
- blueprint: compose
- sfx: whoosh-cinematic
- asset_candidates:

Scene 1 (0.0–1.6s): on the `ink` ground, a faint arc (a thin `yellow` stroke, ~60% of an ellipse) fades in low in frame, echoing the real site's bottom-of-page orbit line — Asymmetric, lower third, ~40% of frame width.
Scene 2 (1.6–3.4s): above the arc, the phrase "KICKOFF IS COM—" glitch-types in (`discrete-text-sequence` + a glitch flicker on the last two characters) then hard-cuts to blank before the word ever completes — repeats once, slightly faster, still incomplete (a deliberate confusion-marketing withhold, never spelling "COMING").
Scene 3 (3.4–5.0s): the arc brightens and pulses once (`ambient-glow-bloom`); the incomplete phrase flashes a final time and holds, unresolved, into the cut — only subtle jitter on the arc's glow, no breathing, no completion.

focal: (abstract SVG arc + typographic fragments — no photographic asset)

narrativeRole: Peak urgency without ever paying off the sentence — hands the unresolved tension straight into the CTA close.
keyMessage: It's almost here. It's not explained. It's not shown.

## Frame 6 — Waitlist close

- scene: Ground holds near-black; the real fancup mark (soccer-ball icon + wordmark) settles centered, the real subhead "The first arena where both worlds collide." fades in beneath in lime green, then "JOIN THE WAITLIST NOW" resolves as a bold CTA button-styled line with fancup.trenchroyale.com beneath it.
- duration: 8s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/06-waitlist-close.html
- type: cta
- persuasion: Scarcity/urgency + Authority by association (Chiliz + Solana ecosystems)
- beat: urgency → anticipation
- blueprint: logo-assemble-lockup (Adapt)
- sfx: whoosh-cinematic, chime
- asset_candidates:

Adapt: Brand_Outro variant — no feature-pill formation to disperse; the signature move is the real mark settling into its held final lockup, matching the real waitlist page's own layout (mark → headline energy → CTA), compressed to fit this frame's copy (subhead + CTA only, since the headline already ran in Frame 3).
Scene 1 (0.0–1.4s): hard cut to the held `ink` ground (unresolved from Frame 5); a soft green-tinted radial glow blooms in low-amplitude behind center, echoing the real page's background treatment.
Scene 2 (1.4–2.8s): the real fancup mark (lime-green soccer-ball icon + "fancup" wordmark, Inter ExtraBold) scale-pops in centered — small and clean, matching its real proportions, not oversized.
Scene 3 (2.8–4.2s): beneath the mark, the real subhead fades in: "The first arena where both worlds collide." in lime green, Inter SemiBold.
Scene 4 (4.2–6.2s): "JOIN THE WAITLIST NOW" resolves centered beneath as a solid green CTA-button-styled pill (Inter ExtraBold, white on green, matching the real page's button color) via a spring-pop entrance on a smooth long-tail settle — no overshoot.
Scene 5 (6.2–8.0s): "fancup.trenchroyale.com" settles beneath the button in gray (Inter Medium) and everything holds to the end — this frame's one true exit (fade to black in the last ~0.5s); subtle jitter only on the mark's glow until then.

focal: (typographic + the small inline SVG logo mark — no photographic asset)

narrativeRole: Land on the real brand identity and the one action that matches the real page's own ask — join the waitlist, nothing more explained.
keyMessage: fancup — join the waitlist now.
