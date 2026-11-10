# Cinelace website

Public English-language website for Cinelace, an automatic video creation tool using open AI models, planned for Windows and iPad. Maintained separately from the private application repository.

This is a static HTML/CSS site. Publish the `main` branch root with GitHub Pages; no build step is required. The planned public URL is `https://nikkittap.github.io/cinelace-app/`, or `https://nikitapetrovapps.com/cinelace-app/` once the user site's custom domain is connected.

Cinelace is clearly marked as in development. The page describes the local-first travel-video workflow and uses the existing application icon.

Shared brand styles and local-preview links are copied from the adjacent `nikkittap.github.io` checkout with `python tools/sync-studio.py` from that checkout. Product-specific styles live in `style.css`.
