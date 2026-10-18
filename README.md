# IsMemoryReallyBeingRestored

An interactive photo archive with 85 original/restoration sequences and 352 photographs.

The complete static site is `index.html` and `images/`. Publish both together at the repository root with GitHub Pages. All image URLs are relative to the page and versioned with the HTML in this repository.

The photo wall progressively loads 420px thumbnails with six concurrent requests. Full photographs (up to 1600px) load on demand. Failed or stalled requests show a retry action. Existing restoration effects, zoom, drag, Chinese/English controls and the final dissolve are preserved.

Open `index.html` locally, or serve this directory with a static HTTP server. No build step, external image host, JavaScript library or backend is required.
