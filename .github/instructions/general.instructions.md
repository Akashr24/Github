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
