# Mapping Indian Art — Design Direction

## Approach 1
**Theme Name:** Archive at Dusk  
**Very Brief Intro:** A dark, cinematic museum interface with indigo-black surfaces, brass highlights, and luminous map lines. It feels like an after-hours exhibition, but risks reducing the tactile warmth of the subject.  
**Probability:** 0.03

## Approach 2
**Theme Name:** Monsoon Field Notes  
**Very Brief Intro:** A quiet editorial atlas built from cream paper, rain-washed blue, ink, and terracotta. It treats the map as a research instrument: precise enough for study, atmospheric enough to invite wandering.  
**Probability:** 0.07

## Approach 3
**Theme Name:** Festival Geometry  
**Very Brief Intro:** A vivid, modular system inspired by textile pattern, block printing, and exhibition signage, with saturated pigment blocks and sharp graphic labels. It is energetic and legible, but less contemplative.  
**Probability:** 0.02

## Selected Direction: Monsoon Field Notes

### Design Movement
Contemporary editorial cartography with references to Indian modernist book design, museum wayfinding, field journals, and monsoon-season material culture.

### Core Principles
1. Geography is the primary story: the map owns the first screen and every content section returns to place.
2. Evidence feels collected: cards, labels, captions, and dividers resemble a carefully annotated atlas rather than a dashboard.
3. Restraint creates reverence: color appears in measured pigment accents, while cream space lets images and facts breathe.
4. Every interaction rewards curiosity: hover, filter, search, and selection should reveal another layer of context without interrupting flow.

### Color Philosophy
The base is mineral cream, like uncoated paper or limestone, so the visual field feels calm and archival. Deep indigo carries authority and gives the map a night-sky depth without becoming a dark-mode interface. Terracotta marks human presence and earth; muted gold signals discovery and heritage; a restrained moss accent separates natural and regional stories. The signature brand color is **Rain-ink Indigo (#24324B)**, an ownable blue-black that feels like wet pigment on a field notebook.

### Layout Paradigm
Use an asymmetric atlas spread: a narrow editorial rail establishes context while a broad map stage carries the interaction. Long sections alternate between edge-aligned headings and offset content clusters. On smaller screens, the rail becomes a compact context bar and the map remains the anchor rather than collapsing into a generic card grid.

### Signature Elements
- Fine longitude/latitude rules and annotated index numbers, used as quiet cartographic texture.
- Terracotta map pins with small gold halos, paired with compact region/category chips.
- A vertical “field note” rail for stats, sources, and the currently selected location.

### Interaction Philosophy
Interactions should feel like handling a well-made atlas: direct, tactile, and reversible. Filters visibly reduce the map set; clicking a tradition card focuses the corresponding locations; a selected site opens a side panel with clear next/previous navigation; reset is always one gesture away. Hover states use elevation and pigment shifts, never noisy effects.

### Animation
Use short ease-out transitions for chips, markers, and buttons. Let the map stage fade and slide by a few pixels when its active selection changes. Side panels enter from the right with a 260ms transform/opacity transition; selected map pins gain a soft pulse only once, then settle. Stagger initial region cards by 45ms. Respect prefers-reduced-motion by removing nonessential map pulses and entrance transforms.

### Typography System
Display headlines use **DM Serif Display** for a literary, exhibition-catalogue voice. UI labels and body copy use **Manrope** for clean legibility. H1 is oversized and tightly tracked; section labels are uppercase Manrope at 0.14em with generous spacing; body copy is 15–17px with 1.65 line height. Numeric stats use Manrope medium with tabular-feeling spacing.

### Brand Essence
A spatial field guide to the places and practices that shaped Indian art, made for students and curious cultural travelers who want to understand heritage through geography.  
**Personality:** observant, grounded, generous.

### Brand Voice
Headlines are concise, evocative, and place-led. CTAs are invitational and specific. Microcopy sounds like a museum educator who respects the visitor’s intelligence.

- Example headline: “Follow the pigment, stone by stone.”
- Example CTA: “Open the field note”

### Wordmark & Logo
The mark is a small indigo compass-window symbol: a four-point star nested inside an open square, with one terracotta corner suggesting a map pin and a page fold. It is intentionally symbol-only so it remains recognizable at favicon size; the wordmark is set separately in DM Serif Display with a custom clipped crossbar on the “A”.

### Signature Brand Color
**Rain-ink Indigo — #24324B**

## Style Decisions
- The map is the hero, not a decorative backdrop.
- Use cream/indigo/terracotta/gold as the core palette; avoid purple gradients and generic SaaS styling.
- Keep decorative pattern sparse and aligned to cartographic lines.
- Use generated imagery only for the hero visual and brand mark; use museum/institutional imagery sparingly and label sources in the UI.
