# 4RnH Mk.1 — Today (GM1)

This package is a **whole drop-in** for your GitHub → Vercel flow, using the new tagging convention.

## Files
- `index.html` — deployable scaffold with a 12x17 grid placeholder.
- `styles.css` — base colours approximating the Excel accents you specified.
- `vercel.json` — static deploy with a catch-all route for SPA-style hosting.
- `assets/icons/*` — favicon + Gavaroso mini 'G'.

## Deploy steps (GitHub → Vercel)
1. Create or open your repo. Click **Add file → Upload files** and drag **the contents of this folder**.
2. Commit directly to `main`.
3. GitHub → **Releases → Draft a new release**:
   - **Tag:** `mk1-today-gm1` (create new tag on `main`)
   - **Tick:** *This is a pre-release*
   - **Title:** `GM 1: Mk1 Today`
4. Publish. Vercel will pick up `main` automatically if connected.

## Notes
- Treat this as a GM scaffold to practice the end-to-end flow.
- We can iterate visuals/content in `mk1-today-gm2` or `mk1-today-gm1-r1`.
