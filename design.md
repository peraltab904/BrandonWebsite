# Brandon Peralta — Design System

A warm, paper-based foundation with bold, confident type. Earthy and trustworthy, but never quiet. Built for student ministry: writing, sermons, recipes, and connecting with students, parents, and fellow leaders.

**Personality:** Bold & energetic · Warm & approachable · Trustworthy & pastoral

---

## Color

### Brand
| Token | Hex | Use |
|---|---|---|
| Clay | `#C05D3C` | Primary accent — buttons, links, energy |
| Sage | `#7E9078` | Calm, pastoral secondary |
| Ochre | `#C98A35` | Warm highlight, used sparingly |
| Ink | `#2B2620` | Headlines & body text |

### Neutrals
| Token | Hex | Use |
|---|---|---|
| Paper | `#F6F1E7` | Page background |
| Sand | `#EFE6D5` | Subtle fills, secondary buttons |
| Card | `#FFFDF8` | Card surfaces |
| Muted | `#6B6155` | Secondary text, captions |

**Rules**
- One accent at a time. Clay leads; Sage/Ochre support, never compete.
- Body text is always Ink on Paper/Card — never colored.
- Dark surfaces use Ink `#2B2620` with Paper text and a Clay or Ochre accent.

---

## Typography

Two families. **Montserrat** is the voice (display + UI). **Lora** is the warmth (body + editorial).

| Role | Family | Weight | Size | Case |
|---|---|---|---|---|
| Display | Montserrat | 800 | 72px / clamp | UPPERCASE |
| H1 | Montserrat | 800 | 40px | UPPERCASE |
| H2 | Montserrat | 700 | 28px | Sentence |
| Article title | Lora | 600 | 24px | Sentence |
| Body | Lora | 400 | 17px | Sentence |
| Body small | Lora | 400 | 14px | Sentence |
| Pull quote / scripture | Lora | 400 *italic* | 18–22px | Sentence |
| Overline | Montserrat | 700 | 12px | UPPERCASE, `.18em` tracking, Clay |
| Label / nav | Montserrat | 600 | 12px | UPPERCASE, `.13em` tracking |
| Meta / mono | ui-monospace | 400 | 11–12px | — |

**Rules**
- Display & headings: Montserrat, tight tracking (`-.01em`), default UPPERCASE.
- Long-form reading (blog, sermon notes, recipes): Lora, line-height ~1.7.
- Scripture references and pull quotes: Lora *italic*.
- Body measure: 52–54ch max.

**Weights loaded:** Montserrat 400/500/600/700/800/900 (+ italic 500); Lora 400/500/600 (+ italic 400/500).

---

## Spacing & Shape

- **Radius:** 2–3px on buttons/tags/inputs, 5–6px on cards and large blocks. Pills use `100px`.
- **Section rhythm:** 64px between major sections; 1120px max content width; 40px page gutters.
- **Borders:** 5px top rule on the page; 2px Ink rule under section headers; 1px `rgba(43,38,32,.12)` hairlines on cards.
- **Paper texture:** optional 34px grid, `rgba(43,38,32,.055)` lines.

---

## Components

### Buttons
- **Primary** — Clay fill, white text, 700 uppercase `.08em`, 2px radius. Hover: `brightness(.92)`.
- **Outline** — 2px Ink border, transparent. Hover: Ink fill / Paper text.
- **Soft** — Sand fill, Ink text. Hover: darker sand.
- **Pill (small)** — 1.5px muted border, `100px` radius, 12px uppercase.

### Links
- **Standout** — Montserrat 700 uppercase, 2px Clay underline, `.14em` tracking.
- **Inline editorial** — Lora *italic*, Clay, thin underline, trailing `→`.

### Forms
- Inputs: Card bg, 1.5px `rgba(43,38,32,.25)` border, 3px radius, Lora 16px. Focus → Clay border.
- Labels: Montserrat 700, 11px uppercase `.1em`.
- **Newsletter block:** Ink surface, Clay overline, Lora invite copy, joined input + Clay "Join" button.

### Tags / Categories
7px×14px, 11px uppercase `.1em`, 2px radius.
- Sermon → Clay fill / white · Recipe → Sage fill / white · Blog → Ochre fill / Ink · Topics → outline.

### Content cards
- **Blog** — 16:10 image, Clay category overline, Lora title, meta + "Read" link.
- **Recipe** — Sage "Recipe" badge, Lora title, time/serves/level stats, Sage "Get the recipe" link.
- **Sermon** — Ink surface, Clay badge, play button, Lora title + italic scripture ref, duration + "Listen".

### Connect block
Full-width Clay panel, "Let's talk" overline, big uppercase headline, Lora invite copy, Paper CTA button → schedule a meeting.

---

## Voice

Warm, direct, pastoral. Speak plainly about ordinary moments. Headlines are confident and short; body copy is honest and unhurried. Scripture is cited, never decorative.

---

## Files
- `Brandon Peralta Design System.dc.html` — living, editable design system (source).
- `Brandon Peralta Design System.html` — standalone, shareable build.
- `design.md` — this spec (source of truth for tokens & rules).
