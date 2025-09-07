# girls-site

Simple static site for 1st Grade Girls Soccer — Fall 2025.

## Deploy steps (GitHub-first)
1. Create a new repo named **girls-site** under your GitHub account.
2. Upload the entire contents of this folder (keep `index.html` at the repo root).
3. On Netlify: **New site from Git** → pick the repo → Build command: *(blank)* → Publish directory: `/`.

## Snacks
- Button in header opens your editable Google Sheet.
- Calendar reads the `gid=471860143` tab and injects the volunteer name onto game days.
- Make sure the sheet is **Anyone with the link: Viewer or Editor**.

**Expected columns** (case-insensitive): `Date`, `Name` (or `Volunteer`/`Snack`).

## Photos
- Put images into `/pics/` and list them in `pics/gallery.json`:
```json
{
  "images": [
    {"src": "pics/team1.jpg", "alt": "First practice"}
  ]
}
```
