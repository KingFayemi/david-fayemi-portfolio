# Netlify deploy

GitHub repo: **https://github.com/KingFayemi/david-fayemi-portfolio**

## Connect Netlify (one-time)

1. Sign in at [app.netlify.com](https://app.netlify.com)
2. **Add new site** → **Import an existing project** → **GitHub**
3. Authorize Netlify if prompted, then select **`david-fayemi-portfolio`**
4. Build settings (should match `netlify.toml`):
   - **Branch:** `main`
   - **Build command:** *(leave empty)*
   - **Publish directory:** `.`
5. Click **Deploy site**

After the first deploy, every `git push` to `main` updates the live site automatically.

## Custom domain (optional)

Netlify → **Site configuration** → **Domain management** → **Add a domain**

Point your DNS to Netlify (A/CNAME records as shown in the dashboard).

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080/
