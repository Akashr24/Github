---
applyTo: "**"
---

# General Instructions

## Mandatory Development Checklist
- **Lint**: Run `uv run ruff check .` to check code quality and style.
- **Build**: Run `uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000` to start the development server.
- **Test**: Run `uv run pytest` to execute unit tests.

## No Simple Browser
Never use the Simple Browser or `open_simple_browser` to preview the application. When running the app, just start it and confirm it's running — do not open any browser preview.

## CSS Styling Practices
Use custom CSS utility classes from `app/static/css/app.css` for consistent styling. Key utilities include layout (flex, grid), spacing (padding/margin), colors (bg/text), typography (sizes/weights), and effects (borders/shadows). Compose classes for complex layouts and add new utilities following existing patterns.

## Frontend Design Guidelines
Create distinctive, creative frontends avoiding generic AI aesthetics. Focus on unique typography, cohesive color themes with sharp accents, meaningful motion/animations, and atmospheric backgrounds. Match implementation complexity to design vision—maximalist designs need elaborate code, minimalist need precision. Avoid overused fonts, clichéd colors, and predictable layouts. Commit to context-specific character and vary aesthetics across designs.

### Design Guide

#### Typography
- Use distinctive fonts: Avoid Arial, Inter, Roboto. Opt for unique choices like Space Grotesk, Cal Sans, or display fonts for headers.
- Hierarchy: Large, bold headings with clean body text.
- Readability: Ensure sufficient contrast and spacing.

#### Color Palette
- Dominant colors with sharp accents.
- Avoid timid, evenly-distributed palettes.
- Use CSS variables for consistency: `--primary`, `--accent`, `--muted`.
- Draw from IDE themes or cultural aesthetics for inspiration.

#### Motion & Animation
- Focus on high-impact moments: Staggered reveals with `animation-delay`.
- Use CSS-only solutions for Jinja2 templates.
- Prioritize meaningful interactions over scattered micro-animations.

#### Layout & Composition
- Avoid predictable patterns: Don't default to centered hero + grid.
- Create atmosphere with layered backgrounds and geometric elements.
- Use CSS gradients, patterns, or contextual effects.

#### Implementation Principles
- Maximalist visions require elaborate code with extensive animations.
- Minimalist designs need precision and careful attention to spacing/typography.
- Elegance comes from executing the vision well, not minimal code.

#### Common Pitfalls to Avoid
- Generic AI slop: Purple gradients, clichéd color schemes.
- Overused fonts and predictable layouts.
- Cookie-cutter components lacking character.
