---
format: 1080x1920
message: "The SECURE Act 2.0 10-year rule changed how you must withdraw an inherited IRA — know the exemptions and the RMD catch, or the IRS penalty finds you."
arc: concept-explainer
audience: "adults who've inherited or expect to inherit an IRA; no tax background assumed"
---

## Video direction

**Palette system** (from `frame.md`, remixed dark-ground brand) — `{colors.bg}` navy (#0B1E3C) is the universal ground on every frame; `{colors.primary}` gold (#D4AF37) is the single accent carrying every eyebrow, numeral, CTA, progress fill, and card border; `{colors.text}` cream (#F5F1E6) carries every headline; `{colors.text-muted}` / `{colors.text-light}` grays carry body/support copy. No second accent color. `{colors.positive}`/`{colors.negative}` stay reserved (unused here — no directional chips in this video).

**Motion grammar + reveal model** — long-tail `power3` settles by default; no bounce/overshoot except the two named exceptions below. This video is **silent** (no voiceover) — every frame paces its reveals to an internal beat grid instead of a spoken cue (same anti-front-load discipline: at t=0 show only the frame's opening element, then reveal each further piece on its own beat, concentrated in the back ~50% of the shot). During any hold, the only sanctioned aliveness is **subtle jitter** (`sine-wave-loop`, low amplitude) — no lazy breathing, no back-half pan/push.

**Earned overshoot (the only two exceptions to power3)**: the inner-edge badge pop in Frame 6 (`comparison-split`'s signature punctuation) and the CTA pill pop in Frame 9. Everywhere else, settle smooth.

**Rhythm / held-frame allocation** — Frames 3 and 8 are the video's two "hero landing" holds (the rule's name; the leverage numeral) — each lands its numeral, blooms a soft gold glow behind it, and holds still to let it read. Frame 5's list holds with only a barely-perceptible sine float once assembled. All other frames reveal-then-brief-hold; none holds longer than ~1.5s once resolved.

**Framing variety** (≥3 used) — centered hero type/numeral (Frames 1, 2, 3, 7, 8, 9), asymmetric card top-anchored (Frame 4), full-width vertical list (Frame 5), split-screen mirrored cards (Frame 6).

**Negative list** — no lazy breathing; no slow pan/push in any back-half; no bouncy/elastic easing outside the two earned exceptions above; no purple-blue "AI" gradients or floating bokeh; no infinite/looping motion (`repeat`/`yoyo`) — all aliveness is a finite tween over the hold; no `Math.random()`/`Date.now()`; no browser chrome, cursors, or nav bars (nothing here reconstructs a real interface). Caption band (bottom ~17%) stays clear on every frame; centered heroes anchor at y ≈ 0.42 × 1920 ≈ 806px, not the canvas midpoint.

## Frame 1 — Hook

- type: hook
- persuasion: Stakes / consequence
- beat: Intrigue + concern
- scene: Navy cover card, gold accent-line, bold headline punches in
- duration: 4s
- transition_in: cut
- status: outline
- voiceover:
- src: compositions/frames/01-hook.html
- blueprint: kinetic-type-beats (Adapt — Hook/flash variant)
- focal: the headline itself
- roles: headline = foreground subject · navy field = background · gold accent-line = supporting
- sfx: none (silent project)

narrativeRole: Opens a stakes gap — inherited IRAs are no longer what most people assume.
keyMessage: The rules for inherited IRAs changed, and most beneficiaries don't know it yet.

Adapt: keep the hard-cut flash-in signature; split one sentence across two beats instead of a single stationary line, so the "changed" lands as its own punch.
Scene 1 (0.0–1.6s): solid navy field. Bold cream "Inherited an IRA?" flash-cuts in dead-center (hard-cut, no fade) — Centered, ~45% of frame. A thin gold accent-line draws in beneath it, left→right.
Scene 2 (1.6–3.2s): hard-cut swap: the question clears and "THE RULES JUST CHANGED" cuts in, larger and bolder, in cream with the word "CHANGED" set in gold — same center anchor, no roll/slide.
Scene 3 (3.2–4.0s): holds; gold accent-line brightens briefly under "CHANGED" (a single settle, not a loop); at most subtle jitter (`sine-wave-loop`, low amplitude) to the end.

## Frame 2 — The stakes

- type: pain_point
- persuasion: Common-belief vs reality
- beat: Concern + surprise
- scene: Centered kinetic type, per-word build contradicts the old "stretch it out" assumption
- duration: 4s
- transition_in: crossfade
- status: outline
- voiceover:
- src: compositions/frames/02-stakes.html
- blueprint: kinetic-type-beats (Adapt — Problem variant)
- focal: the contradicting headline
- roles: headline = foreground subject · gold underline = supporting · navy field = background
- sfx: none

narrativeRole: Kills the outdated "stretch IRA" assumption so the viewer knows old advice no longer applies.
keyMessage: You can no longer stretch withdrawals over your lifetime — that option is gone for most heirs.

Adapt: one pain statement instead of 3-5, built in three word-chunks rather than landing whole.
Scene 1 (0.0–1.4s): navy field; cream phrase assembles via per-word staggered reveal, chunk 1 lands — "You can't" — Centered, upper-third.
Scene 2 (1.4–2.6s): chunk 2 lands beside/below it — "stretch it out anymore" — a gold underline draws left→right beneath "stretch it out" as it lands.
Scene 3 (2.6–4.0s): a smaller supporting line fades up beneath — "The old rules are gone." — settles and holds; subtle jitter only.

## Frame 3 — Name the rule

- type: product_intro
- persuasion: Frame-then-fill
- beat: Clarity + orientation
- scene: Hero numeral card — "10" dominates, "YEAR RULE" beneath, eyebrow tag "SECURE Act 2.0"
- duration: 5s
- transition_in: push-slide UP
- status: outline
- voiceover:
- src: compositions/frames/03-rule-name.html
- blueprint: dataviz-countup (Adapt — Product_Intro variant)
- focal: the "10" numeral
- roles: numeral = foreground subject · "YEAR RULE" label = supporting · eyebrow tag-pill = supporting · navy field with gold glow = background
- sfx: none (silent project)

narrativeRole: Names the mechanism the rest of the video unpacks.
keyMessage: Most beneficiaries must empty the inherited IRA within 10 years of the owner's death.

Adapt: keep the count-up + hero-centering + glow-bloom signature; drop the multi-card scroll (too busy for a single card beat) for one hero metric.
Scene 1 (0.0–1.3s): navy field; gold eyebrow tag-pill "SECURE ACT 2.0" fades up top-center; a very slow continuous camera push-in begins underneath — Centered, upper-third for the tag.
Scene 2 (1.3–3.4s): bold gold numeral counts up 0→10, font-size growing with the value, landing dead-center at y≈0.42×height; cream label "YEAR RULE" fades up beneath it on the same beat — Centered, ~50% of frame.
Scene 3 (3.4–5.0s): soft gold ambient glow blooms behind the numeral; push-in settles to its peak and holds — no further motion; subtle jitter only.

## Frame 4 — How it works

- type: feature_showcase
- persuasion: Frame-then-fill
- beat: Comprehension
- scene: Tinted card — flexible-timing framing, gold progress bar suggesting the 10-year span
- duration: 5s
- transition_in: push-slide UP
- status: outline
- voiceover:
- src: compositions/frames/04-flexible-timing.html
- blueprint: compose (Key_Feature menu doesn't fit a single abstract idea card; built from the motion vocabulary)
- focal: the gold progress bar
- roles: progress bar = foreground subject · headline = foreground subject · tinted card = supporting · navy field = background
- sfx: none

narrativeRole: Clarifies the rule has no fixed annual amount — only a final deadline — before the exemptions and the catch complicate it.
keyMessage: There's no required annual amount — just empty the account by December 31 of year 10.

Compose: from the motion vocabulary — card entrance + per-word reveal + a bars/progress fill (`stat-bars-and-fills`).
Scene 1 (0.0–1.3s): a gold-bordered tinted card fades + slides a short distance into place, top-anchored — Asymmetric, card fills ~70% width, upper two-thirds of frame. Gold eyebrow "HOW IT WORKS" sits above it.
Scene 2 (1.3–3.0s): inside the card, cream headline reveals per-word — "No required annual amount" — landing center-card.
Scene 3 (3.0–5.0s): beneath the headline, a gold progress-bar track fills left→right (`stat-bars-and-fills`) with a tick mark and label "YEAR 10" arriving as the fill completes; settles and holds; subtle jitter only.

## Frame 5 — Who's exempt

- type: feature_showcase
- persuasion: Numbered enumeration
- beat: Comprehension
- scene: Stacked 4-item list card — spouses, minor children, disabled/chronically ill, near-in-age beneficiaries
- duration: 6s
- transition_in: push-slide UP
- status: outline
- voiceover:
- src: compositions/frames/05-exemptions.html
- blueprint: grid-card-assemble (Reproduce — Benefits vertical-list variant)
- focal: the vertical list
- roles: list items = foreground subject · gold check-marks = supporting · eyebrow = supporting · navy field = background
- sfx: none (silent project)

narrativeRole: Establishes who the 10-year rule does NOT apply to, so the viewer can place themselves in or out of it.
keyMessage: Spouses, minor children, disabled/chronically ill heirs, and near-in-age beneficiaries can still stretch withdrawals.

Reproduce: the vertical-list BUILD sub-mode — each line stays lit as the next arrives.
Scene 1 (0.0–1.2s): navy field; gold eyebrow "WHO'S EXEMPT" fades up top-left; an empty vertical list region establishes below it — Full-width strip, top-anchored.
Scene 2 (1.2–4.8s): four items stagger-assemble one by one (~0.9s apart), each via a gold check-mark spring-pop + short mask-wipe text reveal: "Spouses" → "Minor children" → "Disabled or chronically ill" → "Near-in-age heirs" — Full-width vertical list, 4 depth-equal rows.
Scene 3 (4.8–6.0s): completed list holds; a gentle, barely-perceptible sine float runs across the rows (`sine-wave-loop`, low amplitude) — no breathing scale, position only.

## Frame 6 — The catch

- type: feature_showcase
- persuasion: Counterexample
- beat: "Aha" + unease
- scene: Split-screen mirrored cards, gold inner-edge badge, the twist most people miss
- duration: 6s
- transition_in: crossfade
- status: outline
- voiceover:
- src: compositions/frames/06-the-catch.html
- blueprint: comparison-split (Adapt — two conditions instead of two features)
- focal: the right-hand card + its badge
- roles: left card = supporting (the assumed case) · right card = foreground subject (the catch) · title line = supporting · dual gold/navy glow = background
- sfx: none (silent project)

narrativeRole: Surfaces the most-missed detail — the 10-year rule can hide an annual requirement — creating the video's central "aha."
keyMessage: If the original owner had already started RMDs, you must also take annual withdrawals in years 1-9, not just empty it by year 10.

Adapt: keep the mirrored book-open entry + inner-edge badge signature; the two "features" become the two possible conditions the rule can hide.
Scene 1 (0.0–1.0s): centered gold title "THE CATCH" slides down into place from just above, a short smooth settle.
Scene 2 (1.0–3.4s): two equal-width cards arrive from opposite wings with mirrored 3D book-open tilt — left card "Owner hadn't started RMDs / Just empty by year 10" settles first; right card "RMDs already started / + Annual withdrawals, years 1–9" settles ~0.2s behind — Split-screen, mirrored tilt, tilt-matched outward shadows.
Scene 3 (3.4–6.0s): a gold pill badge spring-pops at the right card's inner edge — the one earned overshoot in the video (`spring-pop-entrance`) — reading "MOST MISS THIS"; settles with gentle phase-opposed subtle float on the pair, never synchronized.

## Frame 7 — The penalty

- type: social_proof
- persuasion: Statistical proof
- beat: Relief + confidence
- scene: Centered stat sequence — penalty percentage stepping down, gold numerals
- duration: 5s
- transition_in: push-slide UP
- status: outline
- voiceover:
- src: compositions/frames/07-penalty.html
- blueprint: compose (Social_Proof menu doesn't fit a numeric step-down; built from count-up/data motion vocabulary)
- focal: the stepping percentage
- roles: percentage numerals = foreground subject · supporting labels = supporting · navy field = background
- sfx: none (silent project)

narrativeRole: Grounds the stakes of frame 6 with a concrete, reassuring number — the penalty is real but no longer catastrophic if caught.
keyMessage: Missing a required withdrawal now costs 25% of the shortfall — down from 50% — or just 10% if fixed within two years.

Compose: a count-up/strike-through/count-up sequence — no chart, just the numerals carrying the story.
Scene 1 (0.0–1.2s): navy field; gold eyebrow "THE PENALTY" fades up; large gold "50%" flash-cuts in centered, a strike-through draws across it left→right (`css-marker-patterns`) — the old, harsher penalty, dismissed.
Scene 2 (1.2–3.2s): "50%" clears via hard-cut; gold "25%" counts up centered (`counting-dynamic-scale`) with cream label "if missed" beneath it — Centered.
Scene 3 (3.2–5.0s): a smaller "10%" ticks in beside/below with label "if fixed within 2 years"; settles and holds; subtle jitter only.

## Frame 8 — The advanced play

- type: benefit_highlight
- persuasion: Reframe (cost → leverage)
- beat: Opportunity + excitement
- scene: Centered hero numeral card, gold "2-3X" dominant, supporting line beneath
- duration: 5s
- transition_in: crossfade
- status: outline
- voiceover:
- src: compositions/frames/08-leverage-play.html
- blueprint: compose (Benefits menu is calm/breather-oriented; this beat needs a hero-numeral landing, built from count-up motion vocabulary)
- focal: the "2-3X" numeral
- roles: numeral = foreground subject · headline = supporting · subtext = supporting · navy field with gold glow = background
- sfx: none (silent project)

narrativeRole: Elevates the RMD phase from a compliance problem to a planning opportunity, introducing life insurance as a leverage strategy.
keyMessage: Planning during the RMD phase can change everything — life insurance can leverage the inheritance 2-3x, turning a tax hit into major tax savings.

Compose: mirrors Frame 3's hero-landing signature (count-up + glow-bloom + hold) so the video's two biggest "aha" numerals feel like a matched pair.
Scene 1 (0.0–1.5s): navy field; cream headline reveals per-word — "Planning changes everything." — Centered, upper-third.
Scene 2 (1.5–3.5s): bold gold "2-3X" counts/scales up centered beneath the headline (`counting-dynamic-scale`), landing at y≈0.42×height; cream label "leverage via life insurance" fades in beside it.
Scene 3 (3.5–5.0s): soft gold ambient glow blooms behind "2-3X"; small cream subtext "= major tax savings" settles below; holds; subtle jitter only.

## Frame 9 — Closing / CTA

- type: cta
- persuasion: Direct address
- beat: Resolve + inspiration
- scene: Centered closing card, gold CTA pill reading the calculator name, soft concentric rings
- duration: 4s
- transition_in: crossfade
- status: outline
- voiceover:
- src: compositions/frames/09-cta.html
- blueprint: kinetic-type-beats (Adapt — CTA variant)
- focal: the CTA pill
- roles: CTA pill = foreground subject · headline stack = supporting · concentric rings = background
- sfx: none

narrativeRole: Closes with a clear, low-friction next action pointing to a specific tool.
keyMessage: Check out our new IRA Maximization Calculator to see what this strategy could mean for you.

Adapt: keep the hard-cut value-line-then-CTA-lockup signature; the "lockup" is a named tool, not a logo.
Scene 1 (0.0–1.2s): navy field with faint concentric gold rings behind center; cream line hard-cuts in — "CHECK OUT OUR" — Centered.
Scene 2 (1.2–2.6s): line clears via hard-cut; bold gold "IRA MAXIMIZATION CALCULATOR" cuts in, larger, centered, wrapping two lines.
Scene 3 (2.6–4.0s): a gold pill CTA badge spring-pops beneath — the video's second earned overshoot — reading "SEE YOUR NUMBERS"; concentric rings hold faintly behind; settles to end.
