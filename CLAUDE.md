# Career Talk

Slidev deck for the UD career talk ("The Unwritten Syllabus"). All slide content lives in `slides.md`; slides are separated by `---`, and a slide's frontmatter (layout, image, class) follows its own `---`.

## Commands

- `npm run dev` — local dev server (opens browser). Private photos/videos only show here.
- `npm run build` — build static site to `dist/`
- `npm run export` — export slides

## Conventions

- **Images:** put local images in `public/` and reference them with a root path (e.g. `/learning_curve.png`). Prefer local files over remote URLs — Unsplash links can 404 and silently leave a slide empty. Verify any remote URL with `curl -sI` before using it.
- **Private media:** personal photos/videos go in `public/private/` (gitignored). Wrap them in the `PrivatePhoto` / `PrivateVideo` components (`components/`), which render only in dev and show placeholder content in production builds.
- **Speaker notes:** each slide has an HTML comment (`<!-- ... -->`) with talk notes; keep them updated when editing a slide.
- **Reveals:** use `<v-click>` for progressive reveal; styling is Tailwind/UnoCSS utility classes.
- **Charts:** generated as PNG into `public/` (SVG charts rendered poorly).

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds with `--base /<repo-name>/` and publishes to GitHub Pages. `dist/` and `node_modules/` are gitignored and must not be committed.
