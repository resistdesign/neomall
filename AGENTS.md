# Repository Guidelines

## Mission

Neo Mall is a static Astro site presenting the Neo Mall concept: a free-to-enter resort-style town square organized around food, play, water, entertainment, work, and community.

## Workflow

- Keep `main` deployable. GitHub Pages publishes from the `dist/` artifact built by CI.
- Use optimized public assets from `public/assets/scenes/` for the website.
- Keep copy grounded in the concept imagery and packet-derived direction. Do not invent tenant commitments, budgets, locations, opening dates, or operating claims.
- Prefer scoped Astro/CSS changes over adding frontend frameworks.
- Run `npm run build` before pushing meaningful site changes.

## Content Standards

- Maintain the concept visual language: cream surfaces, deep navy, teal dividers, burnt orange accents, architectural renderings.
- The site should feel like a polished concept presentation, not a generic mall landing page.
- Keep public claims conceptual unless backed by the packet.
- Do not add public links to PDFs or raw image files. Use imagery as part of composed site sections.
- If new images are generated or extracted, optimize them before committing.

## Deployment

- Custom domain: `neomall.resist.design`.
- Deployment workflow: `.github/workflows/deploy.yml`.
- Required validation: `npm run build`.
