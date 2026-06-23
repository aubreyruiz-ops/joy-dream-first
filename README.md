# Joy — Dream-First Planner (prototype)

A concept prototype of the dream-first event planning flow: pick a vibe visually, get an instant draft plan, then move into a guided workspace with a live checklist and clickable plan pieces (venue, website, registration, budget).

Single static file — no build step.

## Deploy to Vercel

1. Create a new GitHub repo (e.g. `joy-dream-first`) and push these files:
   - `index.html`
   - `vercel.json`
   - `README.md`
2. In Vercel, **Add New → Project → Import** the repo.
3. Framework preset: **Other**. No build command, no output directory needed.
4. Deploy. Your link will be `https://joy-dream-first.vercel.app` (or your chosen name).

## Push commands

```bash
git init
git add .
git commit -m "Joy dream-first planner prototype"
git branch -M main
git remote add origin git@github.com:aubreyruiz-ops/joy-dream-first.git
git push -u origin main
```

## Notes

- Vibe-board and venue photos hotlink from Unsplash's CDN. Fine for sharing a prototype; if a link rate-limits or a photo is removed, the tile falls back to a gradient. For a fully self-contained version, the images can be downloaded into the repo and referenced locally.
- All flows are hardcoded concept logic with placeholder data — not a live model.
