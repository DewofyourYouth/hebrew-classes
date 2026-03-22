# Israeli Visual Prompt Context

Use this file as shared context when generating site designs, images, UI themes, or marketing graphics for this project.

## 1) Creative Direction

Goal: A modern Israeli educational look for a Hebrew-learning site.

Core feeling:
- Mediterranean light
- Tel Aviv modernism
- Clean, practical, direct
- Warm human energy, not corporate cold

Design keywords:
- bright, airy, editorial, geometric, local, bilingual-ready, approachable

## 2) Visual Pillars

1. Light + clarity
- High light backgrounds, strong contrast for text, minimal clutter.

2. Blue-led identity
- Israel-inspired blue and white foundation, supported by sand and sun accents.

3. Urban + Mediterranean balance
- Mix clean grid structure with organic textures and warm photography.

4. Real learning energy
- Use authentic classroom/study moments, handwriting cues, notebooks, whiteboards.

## 3) Color System

Primary:
- `#0057B8` (Israeli blue, main brand)
- `#003A8C` (deep navy for headings)
- `#FFFFFF` (white background and negative space)

Secondary:
- `#EAF2FF` (light blue panels)
- `#D9E6FF` (subtle borders/cards)
- `#F6F8FB` (neutral page background)

Warm accents (sparing):
- `#E9D8A6` (sand)
- `#FFB347` (sun accent)
- `#1F9D8B` (fresh teal for small highlights)

Rules:
- Keep blue-white as the dominant ratio (~80%).
- Use warm accents in small doses (~10-15%).
- Reserve bright accent colors for CTAs and key markers only.

## 4) Typography

Preferred families (Hebrew + Latin support):
- `Heebo`
- `Rubik`
- `Assistant`
- `Alef`

Type style:
- Strong, compact headlines
- Highly readable body copy
- Slightly larger body text than default for language-learning clarity

## 5) Layout + Composition

- Use clear 12-column style grid behavior.
- Generous whitespace.
- Rounded corners should be subtle (not playful bubble UI).
- Cards should feel editorial, not dashboard-heavy.
- Use horizontal rhythm lines/dividers inspired by notebook/worksheet structure.

## 6) Graphic Motifs

Use:
- abstract Mediterranean horizon lines
- soft paper grain
- geometric blocks inspired by Bauhaus/Tel Aviv architecture
- subtle map/grid line hints
- handwritten annotation marks (minimal)

Avoid:
- cliche "tourism Israel" collage style
- heavy flag overlays everywhere
- religious icon overload unless content explicitly needs it
- generic startup gradients unrelated to brand

## 7) Imagery Direction

Preferred photos/illustrations:
- daylight, natural tones
- real streets, cafes, classrooms, notebooks, study desks
- diverse people in learning contexts
- modern Israeli city + everyday life, not staged stock smiles

Image treatment:
- soft contrast lift
- clean highlights
- minimal saturation boost on blue channel

## 8) UI Component Behavior

Buttons:
- Primary: solid blue (`#0057B8`) with white text
- Secondary: white background + blue border/text

Cards:
- white or very light blue background
- thin cool-toned border
- slight shadow, low blur

Links:
- clear blue underlines on hover/focus
- obvious accessibility states

## 9) Motion + Interaction

- Motion should be calm and purposeful (200-350ms).
- Use subtle upward fade-in for sections.
- Avoid flashy parallax or excessive bouncing.

## 10) Cultural + Language Notes

- Design must support Hebrew RTL layouts where needed.
- Keep bilingual readiness (Hebrew + English/Turkish notes as needed).
- Prioritize legibility of Hebrew letterforms over stylistic distortion.

## 11) Distinctive Prompt Pack (Structured)

Use these in the same format you already use for other brands.

### A) Main Brand Prompt (Default)

```json
{
  "brand_identity": "Shiurim BeIvrit - Mediterranean Israeli Editorial",
  "user_input": {
    "specifics": "Specific graphic request goes here."
  },
  "style_components": {
    "medium": "contemporary editorial illustration, gouache + ink wash on lightly textured paper",
    "line_work": "clean geometric linework with selective hand-drawn imperfections, architectural horizon lines, subtle map-grid overlays",
    "atmosphere": "sunlit, confident, practical, culturally grounded, modern Israeli learning energy",
    "decor": "Bauhaus-Tel Aviv geometry, notebook margin lines, Hebrew calligraphy fragments, olive branch accents, Mediterranean skyline silhouettes",
    "color_palette": "Israeli blue (#0057B8), deep navy (#003A8C), white, light sky blue (#EAF2FF), limestone sand (#E9D8A6), sun amber (#FFB347), restrained teal (#1F9D8B)"
  },
  "composition_rules": "clear focal center, generous breathing space, no clutter, one strong hero subject, high legibility zones reserved for Hebrew text",
  "typography_direction": "bold Hebrew-first sans look (Heebo/Rubik/Assistant), strong title hierarchy, compact tracking for headlines",
  "aspect_ratio": "16:9",
  "negative_prompt": "3d render, photorealistic, glossy UI, dark cyberpunk palette, overused flag symbols, tourism postcard cliches, low contrast text, distorted Hebrew letters, watermark",
  "additional": "The URL 'hebrew-classes.com' should be displayed at the bottom."
}
```

### B) Variant Prompt: Negev Dawn Study Mood

```json
{
  "brand_identity": "Shiurim BeIvrit - Negev Dawn Study Poster",
  "user_input": {
    "specifics": "Specific graphic request goes here."
  },
  "style_components": {
    "medium": "vintage-modern educational poster, matte gouache with dry-brush texture",
    "line_work": "soft contour ink lines, subtle topographic marks, hand-inked annotations",
    "atmosphere": "quiet morning light, reflective, disciplined, hopeful",
    "decor": "desert ridgelines, Dead Sea horizon geometry, notebook-paper framing, minimal Hebrew diacritic motifs",
    "color_palette": "mist blue, warm beige, sunrise apricot, muted navy, chalk white"
  },
  "composition_rules": "large title block in upper third, visual depth toward horizon, text-safe center panel",
  "typography_direction": "heavy Hebrew title with softer body text contrast",
  "aspect_ratio": "16:9",
  "negative_prompt": "neon gradients, hard black overlays, AI glitch text, oversharpening, cartoon mascots, visual noise",
  "additional": "Include subtle footer text: 'hebrew-classes.com'."
}
```

### C) Variant Prompt: Tel Aviv Classroom Modern

```json
{
  "brand_identity": "Shiurim BeIvrit - Tel Aviv Classroom Modern",
  "user_input": {
    "specifics": "Specific graphic request goes here."
  },
  "style_components": {
    "medium": "modern flat-illustration with textured print finish",
    "line_work": "crisp vector-like contours softened by grain and ink edges",
    "atmosphere": "bright, urban, forward-looking, friendly academic",
    "decor": "Bauhaus facade blocks, whiteboard marks, notebook stickers, minimal Levant coastal light cues",
    "color_palette": "dominant blue-white, cool gray, light cyan, one warm amber accent"
  },
  "composition_rules": "strong left-to-right and RTL-safe balance, modular blocks, clear CTA area",
  "typography_direction": "Hebrew UI-forward sans, high contrast heading-to-body scale",
  "aspect_ratio": "16:9",
  "negative_prompt": "photo collage, glassmorphism overload, heavy drop shadows, excessive icon clutter, unreadable type",
  "additional": "Place 'hebrew-classes.com' in the footer, centered."
}
```

## 12) Short Prompt (Fast Use)

"Modern Israeli educational editorial style for Hebrew learning: Mediterranean daylight, Tel Aviv Bauhaus geometry, blue-white core palette with sand and sun accents, Hebrew-first bold typography, clean high-legibility composition, subtle notebook and map motifs, warm human study context, no tourism cliches, no heavy flag motifs, no glossy UI."
