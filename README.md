# EMBA — AI Essentials for Leaders · Web Activities

Static, self-contained interactive web activities for the course
**AI Essentials for Leaders** (BU.720.602, EMBA).

Deployed as a single **Render Static Site** (no build step, no backend).

## Structure

```
./
├── index.html            # Landing page linking to the activities
├── scalinglaw/
│   └── index.html        # Scaling Law activity  → /scalinglaw/
└── roc/
    └── index.html        # Confusion Matrix & ROC → /roc/
```

Source originals live in the course-development repo
[`DrGGao/EMBA-AIEL`](https://github.com/DrGGao/EMBA-AIEL) under `dev_web-activity/`.
This repo is the deploy copy (files renamed to `index.html` per folder).

## Deploy (Render)

1. dashboard.render.com → **New +** → **Static Site**
2. Connect this repo, branch `main`
3. **Build Command:** *(leave empty)*
4. **Publish Directory:** `.` (repo root)
5. Create.

URLs:

- `/` — landing page
- `/scalinglaw/` — Scaling Law activity
- `/roc/` — Confusion Matrix & ROC curve

## Notes

- Both activities are fully self-contained. The ROC page pulls Lato +
  Source Serif 4 from Google Fonts (falls back to system fonts offline).
