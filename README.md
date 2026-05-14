# demo

Iron Lady app prototype.

## Open locally

Double‑click **`index.html`** or **`iron-lady-app.html`** in the same folder as **`ironlady/logo.png`** (if you use the logo).

## GitHub Pages

### If you see “There isn’t a GitHub Pages site here” (404)

That almost always means **Pages is not enabled yet** or you opened the **wrong URL**.

1. **Push `main` to GitHub** (repo must contain `index.html` on `main`).  
2. On GitHub: repo **`Yas123wanth/demo`** → **Settings** → **Pages** (left sidebar).  
3. Under **Build and deployment** → **Source**: choose **Deploy from a branch**.  
4. **Branch**: `main`, **Folder**: **`/ (root)`** → **Save**.  
5. Wait **1–3 minutes**, then open (project site — **must include `/demo/`**):

   - **https://yas123wanth.github.io/demo/**  
   - or direct: **https://yas123wanth.github.io/demo/iron-lady-app.html**

Do **not** use only `https://yas123wanth.github.io/` unless you have a separate **username.github.io** repository; that is a different site.

If **Source** only shows **GitHub Actions**, pick that and use a Pages workflow, or ask GitHub to show “Deploy from a branch” for this repo.

### Files that help Pages

- **`index.html`** — root URL loads this, then opens **`iron-lady-app.html`**.  
- **`.nojekyll`** — tells GitHub not to run Jekyll (avoids odd 404s on static files).

### Private repo

GitHub Pages for **private** repos needs a **paid** plan. Use a **public** repo for a free demo, or use Netlify / Cloudflare instead.
