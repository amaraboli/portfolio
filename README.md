# Anthony Maraboli — Mechanical Engineering Portfolio

Static site. No build step, no dependencies. `index.html` is the whole site.

```
├── index.html
├── images/     rendered drawing sheets (PNG) + photos/renders (JPG)
└── docs/       full PDF reports, drawing packages, assembly procedures
```

## Deploy to GitHub Pages

1. Create a new public repo named **`portfolio`**. This gives a URL of
   `amaraboli.github.io/portfolio` — a separate, always-available slot regardless of
   what you use `amaraboli.github.io` itself for later.
2. Upload all three items (`index.html`, `images/`, `docs/`) preserving the folder structure.
3. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`. Save.
4. Wait ~1–2 minutes, then load the URL. Confirm every image renders and every PDF opens.

## Before it goes on the resume

- [ ] Verify all 5 PDF links open (they're the depth links under each project)
- [ ] Confirm the YouTube embed plays — it's `youtube-nocookie`, so it won't load offline
- [ ] Add the LinkedIn URL in the footer (commented placeholder is already in place)
- [ ] Optionally drop `resume.pdf` into `docs/` and uncomment the footer link

## Still to add later

- Sketchfab embed of the piano STLs (files are on Canvas, ME 1670 Individual Project 2)
- Live links for Listening Test Trainer and Art Exam Practice Trainer once hosted
- Harmonic Compass link currently points at the GitHub profile — swap to the direct repo URL

## Editing notes

All styling is in one `<style>` block at the top of `index.html`. Colors are CSS variables
under `:root`. The bordered metadata grid under each project hero is `.titleblock` — it
mirrors the title block on the SolidWorks drawing sheets, so keep new fields in the same
short label / short value format.
