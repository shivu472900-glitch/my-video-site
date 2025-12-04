# My Video Site (Required structure)

This repo contains the minimal required files to host a single MP4 video as a static site.

## Required files
- `index.html`               — main page (serves the video)
- `public/videos/video.mp4`  — REQUIRED: the actual video
- `public/assets/styles.css` — styles
- `.gitignore`
- `render.yaml`              — optional but recommended for Render auto-setup

## Deploy to Render (manual steps)
1. Push this repository to GitHub (or Git provider).
2. Create a **Static Site** in Render and connect to this repository and branch.
   - Publish Directory: `/` (root)
   - Build Command: (leave empty)
3. Deploy. Site will be served at `https://<your-site>.onrender.com`.

> Note: Storing large video files in a git repo can be problematic (size, bandwidth). This structure is required per your request; for production, consider object storage + CDN.