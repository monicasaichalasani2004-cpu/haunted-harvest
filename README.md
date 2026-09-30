# The Bone Cathedral of Hollow Creek

**Category:** Graduate  
**Team:** Monica Sai Chalasani (`@mchalasani1`) and Thirunavukkarasu Palaniappa (`@tpalaniappa1`)

A cinematic, CSS-only Halloween story built with semantic HTML5 and one external stylesheet: `haunted-harvest.css`.

## Concept

The visitor crosses the Bone Gate, enters the Ossuary Forest, and reaches the Bone Cathedral at midnight. The final scene includes a CSS-only summon control that awakens a giant skeleton titan.

## Rubric Coverage

### Required Scene Elements
- Human activity: trick-or-treaters and performers
- Animals: black cat, bats, owl, crow, spider
- Weather: layered fog, drifting clouds, lightning, moonlight
- Believable movement: walking bob, wing/flight paths, swaying trees, floating ghosts, dancing skeletons
- Moving vehicle/object: animated hearse, witch on broom, opening bone gate
- Halloween theme: skeleton guardians, graveyard, ghosts, witch, cathedral, bats, moon, fog

### Visual Design & Story
- Three-chapter narrative with a clear visual progression
- Giant skeleton sentinels and final Bone Titan as focal points
- Layered foreground/background depth and cinematic lighting

### Responsive Layout
- Mobile-first fallbacks and scaling
- `clamp()` typography and responsive scene sizing
- No intended horizontal scrolling

### CSS-Only Interactivity
- `:target` scene navigation
- `:hover` and `:focus-visible` gravestone reveals
- `:checked` Bone Titan awakening interaction
- Keyboard-accessible links, buttons, and checkbox control

### Animation Quality
- Independent timing for fog, clouds, lightning, witch, hearse, skeletons, ghosts, gate, cauldron, trees
- Purposeful movement tied to scene storytelling

### Accessibility
- Semantic sections, headings, navigation, and footer
- Skip link and visible keyboard focus
- Readable contrast
- `prefers-reduced-motion` support
- Interactive gravestones are real buttons

### Code Quality
- Single required external stylesheet
- CSS custom properties for required Halloween palette
- Organized comments/sections and semantic markup
- No JavaScript

### GitHub Collaboration
To earn these points, create real evidence in GitHub. Suggested split:

| Team Member | Suggested Meaningful Work |
|---|---|
| Monica Sai Chalasani (`@mchalasani1`) | Scene 1 + Scene 3 story/UI, accessibility review, final integration |
| Thirunavukkarasu Palaniappa (`@tpalaniappa1`) | Scene 2 animations, responsive testing, README/documentation |

Create at least one issue per teammate, commit changes from both GitHub accounts, and use a pull request or documented review before merging. Do not fake commit history.

## Files
- `index.html`
- `haunted-harvest.css`
- `submission_Template_halloween.html`
- `assets/images/`

## Deployment
Upload the project folder to Codd and verify the live URL on both desktop and mobile.


## Design Notes
This version uses system fonts so the appearance stays consistent on the Codd server without depending on Google Fonts. The project is intentionally organized around three scenes and straightforward CSS animations so each team member can explain the code during review.

### Main CSS ideas used
- `:target` for switching scenes
- `:hover` and `:focus-visible` for interaction
- `@keyframes` for fog, vehicles, characters, lights, and pumpkins
- CSS variables for the required Halloween colors
- media queries for smaller screens
- `prefers-reduced-motion` for accessibility

### Local assets
The project includes simple transparent SVG artwork in `assets/images/` for a pumpkin, bat, and ghost.
