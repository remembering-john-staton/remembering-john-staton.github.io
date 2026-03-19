# John Staton Fan Archive

A fan-curated archive dedicated to the art, characters, and world of John Staton.  
Built as a static site — no backend, no build step, deploys directly to GitHub Pages.

---

## 🗂 File Structure

```
john-staton-fanpage/
│
├── index.html          ← Main landing page (hero, topics, characters, quote, footer)
├── gallery.html        ← All 200 art pieces (coming soon)
├── piece.html          ← Individual piece template, loads via ?id=piece-001
├── theme.html          ← Individual topic page, loads via ?id=war
│
├── data/
│   ├── posts.json      ← Featured posts shown on the homepage
│   ├── topics.json     ← All topics/themes
│   ├── characters.json ← All characters
│   └── pieces.json     ← All 200 art pieces (add yours here)
│
└── img/
    └── pieces/         ← Drop your 200 images here
        ├── piece-001.jpg
        ├── piece-002.jpg
        └── ...
```

---

## 🚀 Deploying to GitHub Pages

1. Create a new GitHub repo (e.g. `john-staton`)
2. Upload all files keeping the folder structure intact
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Hit Save — your site will be live at `https://yourusername.github.io/john-staton/`

---

## ✏️ Adding a New Art Piece

Open `data/pieces.json` and add an entry:

```json
{
  "id": "piece-004",
  "title": "Your Title Here",
  "image": "img/pieces/piece-004.jpg",
  "year": "2022",
  "themes": ["war", "fate"],
  "characters": ["elara-voss"],
  "description": "A description of the piece.",
  "statonNotes": "John Staton's own commentary if available."
}
```

Then drop the image into `img/pieces/` with the matching filename. That's it.

---

## ✏️ Adding a New Character

Open `data/characters.json` and add an entry following the same pattern as existing characters.

---

## 🎨 Customisation

- **Colors** — all defined as CSS variables at the top of `index.html` under `:root`
- **Fonts** — Playfair Display + Cormorant Garamond via Google Fonts
- **Quote** — edit the `.quote-line` spans in `index.html`

---

*Fan archive. Unofficial. All rights belong to their respective owners.*
