# Shared with You — Feed Design Case Study

A design case study exploring a **Shared with You** feed experience for TikTok — how content
friends share with you surfaces in the app, with an interactive prototype and supporting research.

🔗 **Live:** deploy on Vercel (root redirects to the case study)

## Contents

| Path | Description |
| --- | --- |
| `index.html` | Root entry — redirects to the case study |
| `case-study-en.html` | The full case study (English) |
| `showcase.mp4` | Hero demo video |
| `about-me.png` | About-the-designer section image |
| `previous/问题1–4.mp4` | Clips illustrating the existing-experience problems |
| `prototype/` | Interactive prototype |
| `prototype/index.html` | Prototype entry point |
| `prototype/03-shared-feed-tab.html` | Shared-with-you feed tab screen |
| `prototype/support.js` | Prototype logic & data |
| `prototype/assets/` | Profile & post images |
| `prototype/media/` | Video/photo content used in the feed |

## Running locally

It's a static site — no build step. Serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Or just open `case-study-en.html` directly in a browser.

## Deploying to Vercel

Static deploy, no framework:

- **Framework Preset:** Other
- **Root Directory:** `./`
- **Build Command:** none

The root `index.html` redirects to `case-study-en.html`, so the deployment root loads the case study.
