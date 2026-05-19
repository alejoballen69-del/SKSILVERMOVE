# SKSILVERMOVE
Skandia SILVER. Tu futuro financiero merece un plan construido sobre tu vida.

# Skandia Silver Landing MVP

Landing page MVP para comunicar la iniciativa **Skandia Silver / Silver Economy** en México. Esta versión está pensada para revisión interna por negocio, marketing, UX/digital y stakeholders del canal comercial.

## Purpose

El sitio presenta una narrativa simple, humana y trust-first para personas de 45+, con foco en pre-retiro, bienestar financiero, claridad patrimonial y una entrada de baja fricción hacia un diagnóstico o conversación inicial.

## Included files

- `index.html` — landing page lista para publicar en GitHub Pages.
- `assets/favicon.svg` — favicon simple en SVG.
- `assets/preview.svg` — imagen preview para Open Graph / social sharing.
- `README.md` — documentación básica de publicación y edición.
- `.gitignore` — exclusiones mínimas.

## Publishing on GitHub Pages

### Option 1: Simple repo publish

1. Create a new GitHub repository.
2. Upload all files in this folder.
3. Make sure the main file is named `index.html` in the repo root.
4. In GitHub, go to **Settings > Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/root`
6. Save and wait for GitHub Pages to publish.

### Option 2: Drag-and-drop workflow

1. Download the folder contents.
2. Create a repository in GitHub.
3. Drag `index.html`, `README.md`, `.gitignore`, and `assets/` into the repository root.
4. Enable GitHub Pages as above.

## Suggested repo name

`skandia-silver-landing-mvp`

## Editing guide

### Main content areas

Search these section IDs inside `index.html`:

- `#inicio` — hero section
- `#que-es` — what Skandia Silver is
- `#por-que` — why it matters now
- `#como-ayuda` — how Skandia helps
- `#audiencias` — audience blocks
- `#empezar` — starting point / diagnosis
- `#cta-final` — final CTA

### Fast content edits

- Headline: search for `Tu futuro merece un plan que entienda tu vida de hoy.`
- Primary CTA: search for `Iniciar conversación de preparación financiera`
- Audience labels: search for `Personas y empleados`, `Empresas y RH`, `Asesores`

### Brand / visual edits

- Colors are defined near the top of the `<style>` block in `:root`.
- Dark mode colors are under `[data-theme="dark"]`.
- The logo mark is inline SVG inside the `.brand-mark` element.

## Recommended next improvements

- Replace placeholders with a real form, calculator, or scheduler.
- Add legal / compliance footer copy before public publishing.
- Replace `preview.svg` with an exported PNG if social sharing quality becomes important.
- Add analytics events for CTA clicks and section engagement.
- Connect CTA buttons to CRM, calendar, or lead capture workflow.

## Notes

- This is a static HTML project with no build step required.
- External fonts load from Fontshare.
- Theme toggle works without localStorage for iframe-safe previews.
