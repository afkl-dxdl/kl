# KLM Brand Identity

## Overview
KLM Royal Dutch Airlines — founded 1919, the world's oldest airline still operating under its original name. Dutch heritage, international reach. The brand feels trustworthy, human, and quietly confident — not corporate or cold.

---

## Design Principles

**Always read the design principles first:**

```
principles.mnd
```

---

## Colour palette (core tokens)

**Core tokens will get referenced by semantic colour tokens**

### Neutral
| Token        | Hex        |
|--------------|------------|
| neutral-0    | #FFFFFF    |
| neutral-1000 | #000000    |

### KLM Blue
| Token        | Hex        |
|--------------|------------|
| blue-50      | #EAF4FB    |
| blue-100     | #D0E7F6    |
| blue-200     | #A5D5EF    |
| blue-300     | #5EBFE7    |
| blue-400     | #009FD9    |
| blue-500     | #0077CD    |
| blue-600     | #005496    |
| blue-700     | #003D6D    |
| blue-800     | #002746    |
| blue-900     | #001527    |

### Warm Grey
| Token          | Hex        |
|----------------|------------|
| warm-grey-50   | #F5F1ED    |
| warm-grey-100  | #EBE2DB    |
| warm-grey-200  | #D4CCC6    |
| warm-grey-300  | #BAB3AD    |
| warm-grey-400  | #9A948F    |
| warm-grey-500  | #797471    |
| warm-grey-600  | #565250    |
| warm-grey-700  | #3E3B3A    |
| warm-grey-800  | #272524    |
| warm-grey-900  | #151413    |

### Green
| Token      | Hex        |
|------------|------------|
| green-50   | #DAFADA    |
| green-100  | #B7F1BA    |
| green-200  | #99DEA6    |
| green-300  | #73C58B    |
| green-400  | #40A469    |
| green-500  | #287D52    |
| green-600  | #1C5D47    |
| green-700  | #0F433A    |
| green-800  | #0A2B26    |
| green-900  | #051714    |

### Red
| Token    | Hex        |
|----------|------------|
| red-50   | #FFEEF6    |
| red-100  | #FFD9E3    |
| red-200  | #FEBEC6    |
| red-300  | #FD989E    |
| red-400  | #FC6063    |
| red-500  | #D42A1E    |
| red-600  | #A02118    |
| red-700  | #751811    |
| red-800  | #4C100B    |
| red-900  | #2A0906    |

### Yellow
| Token       | Hex        |
|-------------|------------|
| yellow-50   | #FFF3BA    |
| yellow-100  | #FEE35D    |
| yellow-200  | #E8CE4B    |
| yellow-300  | #CCB43D    |
| yellow-400  | #A9942F    |
| yellow-500  | #857424    |
| yellow-600  | #5E5319    |
| yellow-700  | #443C13    |
| yellow-800  | #2B260C    |
| yellow-900  | #171407    |

### Orange
| Token        | Hex        |
|--------------|------------|
| orange-50    | #FEEFD9    |
| orange-100   | #FCE0B3    |
| orange-200   | #FAC571    |
| orange-300   | #F6A21A    |
| orange-400   | #D1830A    |
| orange-500   | #A96500    |
| orange-600   | #784800    |
| orange-700   | #573400    |
| orange-800   | #382100    |
| orange-900   | #1D1200    |

### Blue Purple
| Token            | Hex        |
|------------------|------------|
| blue-purple-50   | #ECF3FD    |
| blue-purple-100  | #D7E4FC    |
| blue-purple-200  | #BDCEFC    |
| blue-purple-300  | #9BB1FD    |
| blue-purple-400  | #728EFD    |
| blue-purple-500  | #4465FE    |
| blue-purple-600  | #3048B6    |
| blue-purple-700  | #233484    |
| blue-purple-800  | #162154    |
| blue-purple-900  | #0C122E    |

### Purple
| Token       | Hex        |
|-------------|------------|
| purple-50   | #F5EFFF    |
| purple-100  | #EADDFE    |
| purple-200  | #DBC4FB    |
| purple-300  | #C9A4F8    |
| purple-400  | #B07BF4    |
| purple-500  | #954CEE    |
| purple-600  | #6B35AC    |
| purple-700  | #4E267E    |
| purple-800  | #331753    |
| purple-900  | #1C0C2E    |
 

---

## Semantic colour tokens

**These are linked to core tokens and used for all application**

| Name                          | Core token              | Usage                                                                    |
|-------------------------------|-------------------------|--------------------------------------------------------------------------|
|Surface default                | neutral-0               |default surface colour                                                    |
|Surface contrast               | blue-800                |dark surface for contrast                                                 |
|Surface highlight              | blue-50                 |for highlighting a surface                                                |
|Surface highlight emphasis     | blue-100                |for highlighting a surface on background default                          |
|Surface action primary         | blue-500                |actionable surfaces such as buttons                                       |
|Surface action alternative     | blue-100                |actionable surfaces such as buttons                                       |
|Surface action tertiary        | warm-grey-50            |actionable surfaces such as buttons                                       |
|Surface selected               | blue-800                |selected surface                                                          |
|Background default             | warm-grey-50            |default background                                                        |
|Background alternative         | neutral-0               |alternative (white) background for contrast                               |
|Background scrim               | blue-900                |for contasting layers such as scrims and contrasting gradients            |
|Background high contrast       | blue-900                |for backgrounds that should have very high contrast                       |
|Highlighted title              | blue-200                |to highlight a title on surface contrast                                  |
|Colour brand                   | blue-400                |only used for logo and sky gradient, never for text                       |
|Colour active                  | blue-500                |interactive elements such as links and primaire button                    |
|Colour active contrast         | neutral-0               |interactive elements such as links and primaire button on a dark surface  |
|Text default                   | blue-800                |default text colour                                                       |
|Text active                    | blue-500                |default text colour                                                       |
|Text alternative               | warm-grey-700           |alternative colour for secondairy text                                    |
|Text contrast                  | neutral-0               |contrast text colour on dark surfaces or images                           |
|Text success                   | green-500               |success messages                                                          |
|Text critical                  | red-500                 |critical or warning messages                                              |
|Colour divider light           | warm-grey-100           |dividers on background alternative                                        |
|Colour divider dark            | warm-grey-200           |dividers on background default                                            |
|Border subtle                  | warm-grey-50            |subtle border on background alternative                                   |
|Border default                 | warm-grey-100           |default border                                                            |
|Border contrast                | warm-grey-200           |extra contrast                                                            |
|Border active                  | blue-500                |when a border item becomes selectes or active                             |
|Surface system informative     | blue-200                |surface for nformative notifications                                      |
|Surface system success         | green-100               |surface for success notifications                                         |
|Surface system warning         | orange-100              |surface for warning notifications                                         |
|Surface system crticical       | red-100                 |surface for critical or error notifications                               |
|Colour icon default            | blue-800                |default icon colour                                                       |
|Colour icon contrast           | blue-100                |icon colour on dark surface                                               |
|Surface icon container         | blue-200                |container colour for default icons                                        |

---

## Common colour combinations

- Surface default on background default
- Surface highlight on background alternative
- Surface contrast on background default or background alternative
- Surface highlight emphasis on background default
- Text default on any background or surface
- Highlighted title on surface contrast
- Text contrast on surface contrast
- Colour divider light on background alternative
- Colour divider dark on background default
- Colour icon default on surface icon container


## Typography

### Font families
- **Heading font**: Universal Sans Display
- **Body font**: Universal Sans Text

### Font files (`./assets/fonts/`)

**KLM-branded variants** (use these for the AFKL website):
| File | Weight |
|---|---|
| `KLM UniversalSans-Display-Light.woff2` | Display Light (300) |
| `KLM UniversalSans-Display-Regular.woff2` | Display Regular (400) |
| `KLM UniversalSans-Display-Medium.woff2` | Display Medium (500) |
| `KLM UniversalSans-Display-Bold.woff2` | Display Bold (700) |
| `KLM UniversalSans-Display-ExtraBold.woff2` | Display ExtraBold (800) |
| `KLM UniversalSans-Text-Light.woff2` | Text Light (300) |
| `KLM UniversalSans-Text-Regular.woff2` | Text Regular (400) |
| `KLM UniversalSans-Text-Medium.woff2` | Text Medium (500) |
| `KLM UniversalSans-Text-Bold.woff2` | Text Bold (700) |
| `KLM UniversalSans-Text-ExtraBold.woff2` | Text ExtraBold (800) |

> Fallback stack: `'Helvetica Neue', Arial, sans-serif`

### Fonts per category
- **Display & Headline**: `KLM UniversalSans-Display-Medium` (weight 500)
- **Body & Label**: `KLM UniversalSans-Text-*` — Regular (400), Medium (500), Bold (700)

> **Rule:** All display and headline styles always use `font-weight: 500` (Medium). There is no `--headline-*-weight` token in brand.css — always hardcode `font-weight: 500` when setting display/headline type manually in CSS.

### Display — Universal Sans Display, Medium (desktop ≥720px / mobile <720px)
| Token        | Desktop size / line-height | Mobile size / line-height |
|--------------|---------------------------|--------------------------|
| `display-l`  | 80px / 84px               | 64px / 68px              |
| `display-m`  | 64px / 68px               | 56px / 64px              |
| `display-s`  | 52px / 56px               | 48px / 52px              |
| `display-xs` | 44px / 48px               | 36px / 40px              |

### Headline — Universal Sans Display, Medium (desktop ≥720px / mobile <720px)
| Token           | Desktop size / line-height | Mobile size / line-height |
|-----------------|---------------------------|--------------------------|
| `headline-xl`   | 36px / 40px               | 32px / 40px              |
| `headline-l`    | 28px / 32px               | 28px / 34px              |
| `headline-m`    | 22px / 30px               | 22px / 30px              |
| `headline-s`    | 20px / 28px               | 20px / 28px              |
| `headline-xs`   | 18px / 26px               | 18px / 26px              |

### Body — Universal Sans Text (same size desktop & mobile)
Each size has three weight tokens and a regular-underline variant.

| Token                       | Size / line-height | Font file |
|-----------------------------|-------------------|-----------|
| `body-xl-regular`           | 20px / 28px       | `KLM UniversalSans-Text-Regular.woff2` |
| `body-xl-medium`            | 20px / 28px       | `KLM UniversalSans-Text-Medium.woff2` |
| `body-xl-bold`              | 20px / 28px       | `KLM UniversalSans-Text-Bold.woff2` |
| `body-l-regular`            | 18px / 26px       | `KLM UniversalSans-Text-Regular.woff2` |
| `body-l-medium`             | 18px / 26px       | `KLM UniversalSans-Text-Medium.woff2` |
| `body-l-bold`               | 18px / 26px       | `KLM UniversalSans-Text-Bold.woff2` |
| `body-m-regular`            | 16px / 24px       | `KLM UniversalSans-Text-Regular.woff2` |
| `body-m-medium`             | 16px / 24px       | `KLM UniversalSans-Text-Medium.woff2` |
| `body-m-bold`               | 16px / 24px       | `KLM UniversalSans-Text-Bold.woff2` |
| `body-s-regular`            | 14px / 22px       | `KLM UniversalSans-Text-Regular.woff2` |
| `body-s-medium`             | 14px / 22px       | `KLM UniversalSans-Text-Medium.woff2` |
| `body-s-bold`               | 14px / 22px       | `KLM UniversalSans-Text-Bold.woff2` |

### Label — Universal Sans Text (same size desktop & mobile)
| Token              | Size / line-height | Font file |
|--------------------|--------------------|-----------|
| `label-m-regular`  | 12px / 18px        | `KLM UniversalSans-Text-Regular.woff2` |
| `label-m-medium`   | 12px / 18px        | `KLM UniversalSans-Text-Medium.woff2` |
| `label-m-bold`     | 12px / 18px        | `KLM UniversalSans-Text-Bold.woff2` |
| `label-s-regular`  | 10px / 16px        | `KLM UniversalSans-Text-Regular.woff2` |
| `label-s-medium`   | 10px / 16px        | `KLM UniversalSans-Text-Medium.woff2` |
| `label-s-bold`     | 10px / 16px        | `KLM UniversalSans-Text-Bold.woff2` |

---

## Fixed spacing
In general we stick to fixed spacing. There are exceptions (see dynamic spacing).
For every padding or margin, apply a spacing token.

| Token | Value | Usage |
|---|---|---|
| `--space-4` | 4px | Tight inline spacing |
| `--space-8` | 8px | Between small elements |
| `--space-12` | 12px | Padding for small component like small buttons or chips |
| `--space-16` | 16px | Padding or margin for medium sized components |
| `--space-24` | 24px | Padding or margin for larger component and default space between Cards|
| `--space-32` | 32px | To be determined |
| `--space-40` | 40px | To be determined |
| `--space-48` | 48px | To be determined |
| `--space-56` | 56px | To be determined |
| `--space-64` | 64px | To be determined |
| `--space-80` | 80px | To be determined |


## Dynamic spacing
Different px value for mobile (up to 720px viewport) and desktop for specific use cases

| Token | Value mobile | Value desktop | Usage |
|---|---|---|---|
| `--space-sm`  | 16px | 24px  | Small margin and padding mainly for Cards |
| `--space-md`  | 24px | 32px  | Medium margin and padding mainly for full-width Cards |
| `--space-lg`  | 48px | 64px  | Section margin small for more functional pages |
| `--space-xl`  | 64px | 80px  | Space between page sections |
| `--space-xxl` | 80px | 140px | Section padding top/bottom for experience pages |

---

## Fixed corner radius

| Token | Value | Usage |
|---|---|---|
| `--radius-8`  | 8px  | Selected tab inside segmented controls |
| `--radius-12` | 12px | Small UI components, thumbnails, icon containers, segmented control selected tab |
| `--radius-16` | 16px | **Buttons** (all sizes), **form fields/inputs**, nav pill, segmented control container, modals |
| `--radius-24` | 24px | Content images (not full width) |
| `--radius-32` | 32px | Cards, search box, full width content images or videos |
| `--radius-pill` | 999px | Chips, icon-only pill buttons |

> **Form fields** always use `--radius-16`. **Action buttons** (primary, secondary, tertiary, all sizes) also always use `--radius-16`. **Segmented controls** use `--radius-16` on the container and `--radius-12` on the selected tab. Do not use `--radius-pill` on action buttons — only on chips.

## Corner shape

All elements that have a `border-radius` must also declare `corner-shape: squircle`. Apply this globally via the universal selector so no element is missed:

```css
*, *::before, *::after {
  corner-shape: squircle;
}
```

This gives rounded corners the continuous-curvature squircle shape (as seen on iOS icons and Apple hardware) rather than the standard circular arc. Every radius token in this system — `--radius-8`, `--radius-12`, `--radius-16`, `--radius-24`, `--radius-pill`, `--radius-xl` — renders as a squircle when this rule is in effect.


## Dynamic corner radius

| Token | Value mobile | Value desktop | Usage |
|---|---|---|---|
| `--radius-xl` | 56px | 40px | Expressive corner for hero sections |


## Expressive corner radius
Apply radius-xl on the bottom right corner.

---

## Assets

### Logo
| File | Path | Usage |
|---|---|---|
| Primary logo (blue) | `assets/logo/klm-logo-blue.svg` | Light backgrounds |
| Inverted logo (white) | `assets/logo/klm-logo-white.svg` | Dark/blue backgrounds |
| Icon only (crown) | `assets/logo/klm-crown.svg` | Favicon, small UI |

> The KLM logo consists of the "Flying Dutchman" crown and wordmark. Never distort, recolor, or separate the crown from the wordmark.

### Favicon
- `./assets/favicon.ico`
- `./assets/favicon-32.png`

### Imagery style
- Photography: real people, natural light, warm moments of travel and connection
- Avoid stock-photo feel — authentic, not staged
- Dutch landscapes, Delft blue motifs can appear as subtle decorative elements
- No heavy filters; natural color grading

### Icons
- Use KLM's icon set
- Icon path: `./assets/icons/`

---

## Tone of Voice

- **Trustworthy**: clear, direct, no marketing fluff
- **Warm but efficient**: friendly without being overly casual
- **Dutch directness**: say what you mean, no unnecessary words
- **Helpful**: focused on what the traveller actually needs
- Avoid: superlatives ("the best", "amazing"), jargon, excessive exclamation marks

---

## Button styles

| Variant                    | Background                 | Text             | Border                     | Usage                          |
|----------------------------|----------------------------|------------------|----------------------------|--------------------------------|
| Primary                    | Surface action primary     | text-contrast    | none                       | Main CTA's                     |
| Alternative                | Surface action alternative | text-default     | none                       | Main CTA's with less emphasis  |
| Secondary                  | none                       | text-active      | 1.5px solid border-active  | Secondary actions              |
| Tertiary                   | Surface action tertiary    | text-active      | none.                      | Tertiary actions               |


### Button sizes

| Size | Typography token | Font size | Padding (top/bottom) | Padding (left/right) | Radius |
|------|-----------------|-----------|----------------------|----------------------|--------|
| Small (sm) | `body-s-medium` | 14px / Medium (500) | `--space-12` (12px) | `--space-20` (20px) | `--radius-16` (16px) |
| Medium (md) — default | `body-m-medium` | 16px / Medium (500) | `--space-12` (12px) | `--space-24` (24px) | `--radius-16` (16px) |
| Large (lg) | `body-m-medium` | 16px / Medium (500) | `--space-16` (16px) | `--space-24` (24px) | `--radius-16` (16px) |

- Always use the typography token to set font size and weight — never set `font-size` or `font-weight` directly
- Medium is the default size; apply `sm` or `lg` modifiers only when layout explicitly requires it
- All button sizes use `--radius-16` (16px). This matches the form field radius so inputs and buttons align visually. The `--radius-pill` token is reserved for chips and decorative pill elements — not for primary/secondary/tertiary action buttons.

## Icon button

A fully rounded (pill) button that contains only an icon — no label. Used for destination/action CTAs within image cards and content containers.

| Property | Value |
|---|---|
| Shape | Fully rounded — `--radius-pill` |
| Background | `--blue-200` (`#A5D5EF`) |
| Icon colour | `--blue-800` (`#002746`) |

### Icon button sizes

| Size | Button dimensions | Icon size |
|---|---|---|
| Medium (default) | 48 × 48 px | 24 × 24 px |

- Always use `aria-label` on the button to describe the action (no visible label)
- Icon must come from the `/assets/icons/` library; the default directional icon is `icon-arrow-right.svg`
- Use `--radius-pill` (`border-radius: 9999px`) so the button is always perfectly circular regardless of size
- Corner shape: squircle (inherited from global rule)
- Hover state: `scale(1.08)`; active/press state: `scale(0.96)` — both on `transform` only

---

## Sky gradient

The sky gradient is a decorative brand element — a soft, blurred radial glow in KLM brand blue (`--colour-brand` / `#009FDA` / `blue-400`). It is used behind page headers and hero sections to evoke the sky. It is **never** used as a text colour or UI element; it is always placed on a `::before` or separate element with `z-index: -1` behind content.

The gradient is implemented as an absolutely-positioned overlay with a heavy blur applied via `-webkit-filter`:

```css
/* Desktop — min-width: 768px */
.sky-gradient {
  background: radial-gradient(
    93.34% 152.28% at 32.08% -46.12%,
    #009FDA 0%,
    #009FDAdb 61.01%,
    #009FDA00 100%
  );
  -webkit-filter: blur(32px);
  filter: blur(32px);
  height: 289px;
  left: 40%;
  position: absolute;
  top: -60px;
  transform: translateX(-50%);
  width: 120vw;
  z-index: -1;
  pointer-events: none;
}

/* Mobile — max-width: 767px */
@media (max-width: 767px) {
  .sky-gradient {
    background: radial-gradient(
      94.13% 153.12% at 32.72% -46.96%,
      #009FDA 0%,
      #009FDAdb 61.01%,
      #009FDA00 100%
    );
    left: -12vw;
    top: -98px;
    width: 130vw;
    transform: none;
  }
}
```

**Usage rules:**
- Always use `--colour-brand` (`blue-400` / `#009FDA`) — never `blue-500` or any other blue token
- Always render behind content via `z-index: -1` and `pointer-events: none`
- The parent container must have `position: relative` and `overflow: hidden`
- Do not add additional box-shadows or glows on top of this element

---

## Eyebrows

Eyebrows (section labels above headings) always use **headline-s** — display font, Medium (500), no all-caps, no letter-spacing overrides.

| Property | Value |
|---|---|
| Font | `--font-display` |
| Size / line-height | `--headline-s-size` / `--headline-s-lh` |
| Weight | `500` (Medium) |
| Case | Sentence case — never `text-transform: uppercase` |
| Colour | Context-dependent (`--text-subtle` on light bg, `--text-contrast` with reduced opacity on dark/image bg) |

---

## Borders & dividers

All borders and dividers use **1.5px** stroke weight and the `--border-subtle` token. Never use `1px` or `--border-default` for separators.

| Property | Value |
|---|---|
| Stroke width | `1.5px` |
| Colour token | `--border-subtle` |

---

## Shadows

**No box-shadows on UI elements.** KLM's visual language is flat and relies on borders, background tokens, and white space for separation — not elevation. Do not add `box-shadow` or `drop-shadow` to buttons, inputs, cards, nav pills, or any interactive component. The only exception is modals and floating overlays (e.g. dropdowns, tooltips) where a subtle shadow is required to communicate that an element is detached from the page.

---

## Do's and Don'ts

**Do:**
- Use KLM Blue as the dominant brand color
- Keep layouts clean and uncluttered
- Use ample white space
- Apply the Delft blue ceramic tile motif sparingly as a decorative detail

**Don't:**
- Use KLM Blue on dark backgrounds without sufficient contrast check
- Mix the Air France brand palette with KLM
- Use serif fonts
- Add drop shadows to the logo
