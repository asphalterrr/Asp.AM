# Asp.AM — GitHub Pages website

## Publish
1. Create a **public** repository on GitHub, e.g. `asp-am`.
2. Upload `index.html` and `links.json` to the repository root (not inside a folder).
3. In Settings → Pages choose Deploy from a branch, `main`, `/ (root)`, then Save.
4. Your URL will be `https://YOURUSERNAME.github.io/asp-am/`. Add that URL to guns.lol.

## Add Alight Motion presets
Edit `links.json` on GitHub. It starts as `[]` (no presets). Replace it with:

```json
[
  {
    "title": "My first shake",
    "description": "Alight Motion preset",
    "category": "shake",
    "icon": "💙",
    "url": "https://example.com/replace-with-your-real-link"
  }
]
```

Replace the example URL with your **real** Alight Motion or Google Drive link. To add more presets, put a comma between objects. No preset count limit is imposed by the website. The search searches titles, descriptions and categories.

## Music
Upload an MP3 named **music.mp3** to the same repository folder as `index.html`. Visitors can click **Play music** or **Pause music**. Browsers generally do not allow autoplay without user interaction. Use music you have permission to share.

## Profile picture
Optional: upload `avatar.png` to the same folder. Without it, a wolf emoji appears.

The page contains no preset links until you add them. No YouTube or guns.lol placeholder buttons are included.


## Click-to-enter music
Visitors click **CLICK TO ENTER** to open the preset vault. This click starts `music.mp3` (if uploaded). Browsers generally block unprompted autoplay, so the enter click is required. Visitors can pause/play afterward.
