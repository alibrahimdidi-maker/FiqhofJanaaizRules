# Fiqh al-Janaiz (DIS0702) — Course Slides Site

Same setup as the other module sites: a hero screen (photo, badges, intro,
objectives) with a module-code gate, then all 15 weeks as royal-styled
accordion cards.

## Files

```
index.html       — the whole site (hero + gate + all 15 weeks)
fonts/Faruma.ttf — Dhivehi Faruma font, embedded via @font-face
```

Module code (password): **DIS0702**

## Note

No video link or specific semester/credit numbers were given for this module,
so:
- The hero has no video block (can be added later — see how it was done in
  the SHA0926/HSS0501 sites for the pattern to copy).
- Semester (2026/2), Credits (15), and Continuous Assessment (100%) were
  reused from the Imams Practice module as placeholders. Edit these directly
  in `index.html` if they're different for this module.

## Deploying to GitHub Pages

Same steps as before:
1. Create a new repository (e.g. `fiqh-al-janaiz-slides`).
2. Upload `index.html` and the `fonts/` folder (with `Faruma.ttf` inside),
   keeping the folder structure intact.
3. Settings → Pages → Source: "Deploy from a branch" → `main` → `/ (root)` → Save.
4. Your live link: `https://<username>.github.io/<repo-name>/`

## Hiding weeks not yet taught

Search `index.html` for `LAST_VISIBLE_WEEK` and change the number — weeks
beyond it stay in the file but are hidden from view.
