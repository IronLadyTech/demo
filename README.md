# demo

Iron Lady app prototype.

## Open locally

Double‑click **`index.html`** or **`iron-lady-app.html`** in the same folder as **`ironlady/logo.png`** (if you use the logo).

## GitHub Pages

### If you see 404 (“There isn’t a GitHub Pages site here”)

**A. Use GitHub Actions (recommended for this repo)** — a workflow is in **`.github/workflows/pages.yml`**.

1. Push **`main`** (includes that workflow).
2. GitHub → **`IronLadyTech/demo`** → **Actions** → open **“Deploy to GitHub Pages”** → confirm it **ran successfully** (green). If the org blocks workflows, allow them under org **Settings → Actions**.
3. **Settings** → **Pages** → **Build and deployment** → **Source**: choose **GitHub Actions** (not “Deploy from a branch” if you use this workflow).
4. Wait until the workflow finishes, then open:

   - **https://ironladytech.github.io/demo/**  
   - or **https://ironladytech.github.io/demo/iron-lady-app.html**

**B. Classic “Deploy from branch”** (no Actions)

1. **Settings** → **Pages** → **Source**: **Deploy from a branch** → **`main`** / **`/ (root)`** → Save.  
2. Wait 1–3 minutes, then use the same URLs as above.

**Wrong URL:** `https://ironladytech.github.io/` alone is **not** this project site — you need **`/demo/`** in the path.

### Files that help Pages

- **`index.html`** — root URL loads this, then opens **`iron-lady-app.html`**.  
- **`.nojekyll`** — tells GitHub not to run Jekyll (avoids odd 404s on static files).

### Private repo

GitHub Pages for **private** repos needs a **paid** plan. Use a **public** repo for a free demo, or use Netlify / Cloudflare instead.
