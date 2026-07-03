# Decisions

## 2026-07-03: Static Astro Site

Decision: Build Neo Mall as a static Astro site deployed to GitHub Pages.

Rationale: The project is a concept presentation with rich visuals, fast page loads, and no backend requirements.

Consequences: Content and imagery are versioned directly in the repo. GitHub Actions can build and deploy the site on every push to `main`.

## 2026-07-03: Packet-Derived Visual System

Decision: Use the PDF packet's rendering style, colors, and conceptual language as the source of truth.

Rationale: The supplied packet already defines a strong brand direction and avoids a generic commercial real-estate look.

Consequences: Site copy stays concept-focused and avoids unsupported factual claims.

## 2026-07-03: Scene-First Public Site

Decision: Present the concept as composed HTML sections over optimized scene images rather than linking to the source PDF or raw image files.

Rationale: The public site should feel like a polished web expression of the concept, not a document viewer or file gallery.

Consequences: The site keeps text accessible and responsive while using the renderings as immersive section backgrounds.
