# Investment Market Dashboard

Sanlam Private Wealth index-returns dashboard, data as at **30 September 2026**.

- `index.html` — full dashboard (homepage; phones are sent to `mobile.html` automatically)
- `mobile.html` — phone version

Both files are self-contained: no build step, no dependencies.

## Publish on GitHub Pages
1. Upload `index.html`, `mobile.html`, `og-image.png` and `README.md` to the root of this repo, and delete the old `desktop.html` (Add file → Upload files → Commit).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Live in a minute or two at:
   - https://GuyAllan.github.io/Investment-Market-Dashboard/
4. On a phone, use *Add to Home Screen* to run it like an app.

## Monthly update
Replace both HTML files with the new month's export and commit.

Source: Bloomberg; Stats SA; Sanlam Private Wealth. Past performance is not a guide to future returns.
