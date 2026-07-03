# Repository Guidelines

## Mission

Neo Mall is a static Astro site presenting the Neo Mall 2026 concept: a free-to-enter resort-style town square organized around food, play, water, entertainment, work, and community.

## Workflow

- Keep `main` deployable. GitHub Pages publishes from the `dist/` artifact built by CI.
- Preserve the source PDF and layout image in the repository root unless the project owner asks to move them.
- Use optimized public assets from `public/assets/renderings/` for the website.
- Keep copy grounded in the information packet. Do not invent tenant commitments, budgets, locations, opening dates, or operating claims.
- Prefer scoped Astro/CSS changes over adding frontend frameworks.
- Run `npm run build` before pushing meaningful site changes.

## Content Standards

- Maintain the packet's visual language: cream surfaces, deep navy, teal dividers, burnt orange accents, architectural renderings.
- The site should feel like a polished concept presentation, not a generic mall landing page.
- Keep public claims conceptual unless backed by the packet.
- If new images are generated or extracted, optimize them before committing.

## Deployment

- Custom domain: `neomall.resist.design`.
- Deployment workflow: `.github/workflows/deploy.yml`.
- Required validation: `npm run build`.
