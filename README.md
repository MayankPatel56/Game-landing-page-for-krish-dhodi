# README.md

**Version 1.0.0** | **Status: Operational** | **Type: Horror Landing Page**

## 📁 Project Overview

**LAST YEAR** is a high-fidelity cinematic landing page built to demonstrate modern web design techniques applied to the survival horror genre. The design focuses on high contrast, moody lighting, and an immersive atmosphere replicating a AAA game experience using only vanilla web technologies.

## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| **Cinematic Lighting** | CSS radial gradients and blur filters create a foggy, moonlit forest atmosphere without external assets. |
| **Responsive Layout** | A fluid grid system that adapts from 16:9 desktop cinematic views to vertical mobile perspectives. |
| **Horror Aesthetics** | Blood splatter UI elements, flickering animations (using `@keyframes`), and custom-shaped polygons. |
| **Performance First** | Zero dependencies. No external images, no frameworks, no heavy libraries. Sub-100ms render time. |

## 🛠️ Technical Stack

- **HTML5:** Semantic structure for high-accessibility and SEO potential.
- **CSS3:** Advanced positioning, clip-paths for rugged buttons, and custom animations.
- **JavaScript:** Minimalist scroll-tracking for parallax effects and interactive hover states.
- **Graphics:** Pure CSS and Unicode Emojis utilized for all iconography and characters.

## 💻 Implementation Details

The project follows a single-file architecture for portability within sandboxed environments.

```css
/* The core color palette used for the dark survival theme */
:root {
    --dark-navy: #0b0f1a;  /* Night sky / Shadows */
    --blood-red: #c1121f;  /* Primary Action / Horror */
    --fog-blue: #1f2a44;   /* Atmosphere / Highlights */
}
