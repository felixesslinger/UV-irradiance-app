# UV Irradiance Rectangular Volume (App4)

Single-file web app to explore irradiance and dose in a rectangular chamber (cm geometry), with lamp toggles (222/275 nm), physics parameters, tooltips, unit converter, and interactive probe.

## Quick start (local)
Just open `index.html` in any modern browser.

## Deploy for free

### Option A — GitHub Pages
1. Create a repository, e.g. `uv-irradiance-app`.
2. Add `index.html` to the repo (at the root).
3. In **Settings → Pages**:  
   - Source: **Deploy from branch**  
   - Branch: `main` / **root**  
4. Wait ~30–60 seconds. Your app will be at:  
   `https://<your-username>.github.io/uv-irradiance-app/`

**CLI quick publish**
```bash
git init uv-irradiance-app && cd uv-irradiance-app
cp /path/to/index.html ./index.html
git add index.html
git commit -m "Publish App4"
gh repo create uv-irradiance-app --public --source=. --remote=origin --push
# Then enable Pages in the repo settings (as above).
```

### Option B — Netlify Drop
1. Go to Netlify Drop.
2. Drag-and-drop `index.html`.
3. Get an instant public HTTPS URL. (Create a free account to keep/manage it.)

### Option C — Vercel
1. Push `index.html` to a GitHub repo.
2. Import the repo in Vercel → **Deploy**.
3. Access via `https://<project>.vercel.app/`.

## Notes
- No build step, no backend — pure static HTML/JS/CSS.
- Geometry inputs are **centimeters**; calculations are SI internally.
- Irradiance is in **mW/m²**; dose in **mJ/cm²** (with converter).
- Radiant flux per lamp range: **1–1000 mW**.

## License
Choose whatever you prefer (e.g., MIT). Example:

```
MIT License
Copyright (c) 2025 <Your Name>
Permission is hereby granted, free of charge, to any person obtaining a copy...
```
