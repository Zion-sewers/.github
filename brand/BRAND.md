# Zion brand book

Version 1.0 — 2026-10-13. Owner: Noor · Zion Content.
One page per section. If it does not fit on one page, it does not ship.

## 1. What the brand is

**Zion — public infrastructure for trust in agents.**
Tagline: *the eval layer for the long-horizon era.*
Every repo answers one question: **how do I know I am right?**

Voice: adversarial-honest, evidence-first, zero hype. Verdict first, mechanism
after. Every public number carries its receipt. Prose is not enforcement.

## 2. Typography

| Role | Family | Fallback |
|---|---|---|
| Headings | Space Grotesk | `Inter, system-ui, sans-serif` |
| Body | Inter | `system-ui, sans-serif` |
| Code | JetBrains Mono | `ui-monospace, monospace` |

Rationale: all three are OFL open-source — the licenses match the brand.
Space Grotesk reads engineered without tipping into cyber-slop. Inter is the
neutral workhorse. Nothing decorative, ever.

## 3. Palette

One disciplined direction: **inspection light on warm dark.**
(The watchmaker's lamp, the safecracker's brass, dawn on the bridge.)

| Name | Hex | Use |
|---|---|---|
| Vault | `#101210` | Primary dark. Backgrounds. |
| Bone | `#F5F1E6` | Primary light. Text on dark, light backgrounds. |
| Brass | `#D9A13B` | Primary accent. The one color that means "Zion". CTAs, highlights, key lines. |
| Signal | `#B3402A` | Verdicts. FINDING, REFUTED, danger, failed gates. Never decorative. |
| Slate | `#5C6B5A` | Supporting. Secondary text, borders, quiet structure. |

Rules: Brass is the only accent on dark. Bone text on Vault, never pure white
on pure black. Signal appears only where a verdict is stated. Maximum two
colors per composition besides Vault/Bone.

## 4. Placements

| Surface | Asset | Size |
|---|---|---|
| Org profile | `profile/hero.webp` | 1600×900 |
| Repo READMEs | `docs/hero.webp`, directly under the hook line | 1600×900, full container width |
| Repo social preview | `docs/social-preview.png` | 1280×640, uploaded via repo Settings (UI only, owner action) |
| Blog posts | header image | 1600×900; list thumbnails 800×450 |

Hero rules: one hero per repo, tied to that repo's mechanism (see
`../content/hero-concepts-2026-10-13.md`). Never reuse a hero across repos.
No text baked into images. No banned slop: hooded figures, hologram-touching,
glowing blue networks, code rain, lens flare, generic cyber.

## 5. Asset usage — do / don't

**Logo (the Matrix-generation mark):**
- Do: place on Vault or Bone only. Clear space on all sides = cap-height of the mark.
- Don't: stretch, recolor, rotate, add drop shadows, place on busy photography.

**Heroes:**
- Do: one per repo, cinematic, mechanism-tied, palette-disciplined.
- Don't: reuse across repos, add captions inside the image, use as social avatar.

**Monsters (mascots):**
- Do: claude-memes-skills only. Meme drops, fun surfaces.
- Don't: technical docs, READMEs of other repos, the org profile, the blog.

**Memes:**
- Do: the fun surface. Terminal drops, social.
- Don't: inside technical explanations, reviews, or anything that states a verdict.

**Motion (animated SVG / GIF in READMEs):**
- Do: exactly one animation per README max, and only when it explains a mechanism
  a static image cannot (a flow, a state machine, a scoreboard over time).
- Don't: decorative loops, spinning logos, animated backgrounds. Motion must teach.

## 6. Files in this directory

- `BRAND.md` — this book.
- `palette.css` — the five colors as CSS custom properties.
- `palette.json` — the five colors as JSON.
- `wordmark.svg` — "ZION" wordmark, Space Grotesk with fallbacks.
