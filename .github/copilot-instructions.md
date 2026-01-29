## Project Context
This is a **beginner learning project** for building a pet fostering call-to-action (CTA) website. Focus on teaching clear HTML structure and basic CSS styling that beginners can understand and modify.

## HTML & CSS Guidelines

### Core Principles
- **Beginner-first code**: Use simple, readable syntax. Avoid advanced CSS (no Flexbox, Grid, animations).
- **Semantic HTML**: Use `<header>`, `<section>`, `<button>` instead of generic `<div>` when appropriate.
- **CSS documentation**: Add comments explaining the purpose of each CSS rule (e.g., `/* Blue background for header */`).

### Design System
- **Color Palette**: Blue & teal tones (nature-inspired) for trust and calm. Examples: `#006a6a` (teal), `#e0f2f1` (light cyan).
- **Typography**: Modern, readable fonts. Use generic system fonts: `font-family: Arial, sans-serif;` or `'Segoe UI', sans-serif;`.
- **Layout**: Use basic properties: `width`, `height`, `margin`, `padding`, `text-align`, `background-color`, `color`.

### Common Patterns in This Project

**Background Images with Overlays**: 
- Apply background images with a semi-transparent overlay to ensure text readability.
- Pattern: Set `background-image: url()` and `background-color: rgba()` on same element, or use a pseudo-element overlay.

**Two-Column Sections**:
- Use `width: 50%; display: inline-block;` for side-by-side columns instead of Grid/Flexbox.
- Add `vertical-align: top;` to align columns at the top.
- Example: foster pet info section (`img/pet.jpg` alongside description text).

**CTA Buttons**:
- Style `<a>` or `<button>` with `background-color`, `color`, `padding`, `border-radius` for eye-catching call-to-action.
- Keep contrast high for accessibility (bright button on darker background).

### File Structure
- `index.html`: Main page structure (header, banner, sections).
- `style.css`: All styling (external stylesheet approach).
- `img/`: Contains `cta-bg.jpg` (banner background) and `pet.jpg` (foster section image).

### What to Avoid
- ❌ Flexbox, CSS Grid, media queries
- ❌ CSS animations/transitions
- ❌ Complex selectors (nested, combinators)
- ❌ Advanced positioning (absolute, fixed)
- ❌ CSS preprocessors (SASS/LESS)