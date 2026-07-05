# Lintelgotchi

Raise your own Lintel from The Secrets of Silver Clouds.

This is a static single-page browser game. The playable site lives in `index.html`, with image assets in `images/` and sound assets in `sounds/`.

## Run locally

Open `index.html` in a browser.

For a local server, run this from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Desktop

Use this folder as the repository root:

```text
C:\Users\chris\Desktop\Lintelgotchi-main\Lintelgotchi-main
```

After publishing to GitHub, GitHub Pages can serve the game from the repository root because `index.html` is at the top level.

## Notes

- Background music has an on/off button in the top-right corner.
- The music preference is saved in the visitor's browser with `localStorage`.
