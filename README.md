# FAVLA Project Page

This repository contains the project website for:

**FAVLA: A Force-Adaptive Fast-Slow VLA model for Contact-Rich Robotic Manipulation**

## Contents

- `index.html`: Main page content and section layout
- `static/images/`: Figures used in the paper page
- `static/videos/`: Demo videos for task results, OOD comparisons, and failure cases
- `static/css/`: Bulma and custom styles
- `static/js/`: Frontend utility scripts

## Local Preview

Run a local static server from the repo root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- Videos are compressed for web hosting and GitHub size constraints.
- `<video>` tags use `preload="none"` to reduce initial page bandwidth.
- The page includes contact-rich manipulation results.
- The page includes contact-rich and high-precision results.
- The page includes original vs OOD paired comparisons.
- The page includes generalization studies.
- The page includes failure cases.
