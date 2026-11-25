# Shift website: rules for Claude

This is a plain HTML, CSS and JavaScript site with no build step. Cloudflare Pages publishes it straight from the repo:
framework preset **None**, build command blank, build output directory `/`.

## Rules for every change

1. Make changes on a branch called `preview`, never straight on `main`. Cloudflare gives it a test link at `https://preview.<project>.pages.dev`.
2. Test at desktop and phone width before pushing, and send the preview link with screenshots.
3. Only merge into `main` when Tom says go.
4. Before starting, check whether `preview` has changes Tom hasn't approved yet (commits on `preview` that aren't on `main`), and tell him.
5. If a request could mean two things, ask first.
6. Give exact links, not "go to settings".
7. Never add personal info, passwords, keys or private files.
8. Keep each file under 25 MB. Use `.webp` for images and `.webm` for video.
