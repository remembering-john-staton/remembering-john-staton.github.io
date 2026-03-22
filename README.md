# The John Staton Museum

A fan archive dedicated to the art, characters, and worlds of John Staton (1970s–2026). Maryland-based artist, cartoonist, worldbuilder. DeviantArt presence spanning two decades.

**Live site:** https://remembering-john-staton.github.io

---

## What's here

- **194 pieces** from his DeviantArt gallery, with original descriptions and comment threads preserved
- **Gallery sections** for each of his original IP projects (DMV, The Streamers, N.E. Boox, The High School Romance, Daniel Dukke & Ferdinand Fox) and fan art categories
- **Individual piece pages** with his full artist descriptions, formatted text, emoji/emoticon preservation, and threaded comments
- **Collaborators page** profiling the artists he worked with and the regulars who were part of his community
- **Celebration of life:** https://rememberingjohn.info/

---

## Using this work

John passed away in January 2026. His material is believed to be orphan works with no active rights holder.

**There is no license on this archive.** Use the work. Continue the characters. Make something.

If you fork or build on this, no credit required, no restrictions. The repo is public for exactly that reason.

---

## Tech

Static site on GitHub Pages. No framework, no build step. Plain HTML/CSS/JS.

- `index.html` — homepage with hero, gallery grid, about section
- `piece.html` — individual piece page (loads from `data/pieces.json` via `?id=`)
- `collaborators.html` — friends and collaborators page
- `about.html` — about the site and the work
- `contact.html` — contact form (Google Form embed slot)
- `data/pieces.json` — all 194 pieces with descriptions, comments, versions, topics
- `data/topics.json` — gallery/topic definitions
- `img/pieces/` — 216 images, all named `slug-JohnStaton.jpg/png`

The pieces.json was generated from a DeviantArt archive HTML export. The extraction script is not included in this repo but can be reconstructed from the format.

---

## Contributing

Pull requests welcome — corrections, missing pieces, better descriptions, additional context about characters or projects. Open an issue or just PR.

