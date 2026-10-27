# Boczek Family Card Games — the home page

One static page (no build) at https://louiebo1.github.io/ (repo Louiebo1/louiebo1.github.io,
GitHub Pages from `main`; started 2026-10-25). It lists the card game websites, which live in
their own repos at /hearts, /pinochle, /fivehundred, /cribbage, /gin.

- `index.html` — everything (styles inline). A tile per game: its icon, name, one line.
- `img/` — each game's icon (256 px copies of that repo's `img/icon.png`), the felt from
  Pinochle, and `icon.png` (the four suits on felt, drawn in headless Chrome from HTML).
- Adding a game: copy its icon to `img/`, add an `<li>`, push.
- `docs/ARCHITECTURE.md` + `docs/architecture.png` — how all five games work (hosting, the
  shared Firebase tables, the host pattern); Louie made the diagram in ChatGPT 2026-10-27.
