# FiberTune Project Page

This repository is the static GitHub Pages project page for FiberTune, accepted at CoRL 2026.

Paper: https://arxiv.org/abs/2606.08653

OpenReview: https://openreview.net/forum?id=yNHgrgATuY

Code: https://github.com/fibertune/FiberTune

Deploy options:

1. Push this directory as the root of a GitHub Pages repository.
2. Or copy its contents into a `docs/` directory and select that folder in the
   repository's Pages settings.

No build step is required. The page uses only relative paths:

- `index.html`: public project page.
- `static/css/style.css`: page styling.
- `static/assets/`: figures and image assets.
- `static/videos/fibertune_video.mp4`: project video.
- `.nojekyll`: disables Jekyll processing on GitHub Pages.

Local preview:

```bash
cd FiberTune-project-page
python -m http.server 8000
```

Then open `http://localhost:8000`.
