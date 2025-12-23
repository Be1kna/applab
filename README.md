# Applab Hub

This small site lists Code.org Applab projects and lets you preview them inline using their embed URL.

How to use
- Add Applab entries to `projects.json` (fields: `id`, `title`, `description`, `url`, `embedUrl`, `icon`, `tags`).
- Host this folder as its own repository (e.g. `applab`) and publish with GitHub Pages.

Test locally

```bash
cd ~/Projects/applab
python3 -m http.server 8001
# open http://localhost:8001
```

Notes
- Some sites disallow embedding via headers; if a project doesn't load, open it in a new tab.
- The iframe uses a sandbox for safety (`allow-scripts allow-forms allow-same-origin`).
# applab
