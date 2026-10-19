# Sir Bramble of Asterfall

A tiny adventurer's interactive portfolio: part character dossier, part storybook, and part pixel-art toy box.

## Features

- Original pixel-art scenes and an animated character
- Interactive origin story, map, and quest log
- Day/night theme, sound effects, and optional ambient sound
- Downloadable postcard
- Guestbook wishes stored only in the visitor's browser
- Responsive layout and reduced-motion support

## Run locally

No build step or dependencies are required. Open `index.html` in a browser, or serve this directory with any static file server. For example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Privacy

The project has no backend, analytics, or API keys. Theme, sound, visit count, and guestbook entries use browser-local storage and stay in that browser. Google Fonts are loaded from Google when a network connection is available; system monospace fonts are used as fallbacks.

## Deploy

This is a static site and can be hosted with GitHub Pages. In the repository settings, enable Pages and select the `main` branch and `/ (root)` as the source.
