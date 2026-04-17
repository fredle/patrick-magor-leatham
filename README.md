# Major Patrick Magor Leatham MC

A small tribute website for Major Patrick Magor Leatham MC (1914–1951), 10th Royal Hussars (Prince of Wales's Own), compiled by his family in 2026.

## Hosting

This is a static single-page site. Host anywhere that serves files. Recommended: **GitHub Pages** (free).

## Structure

```
index.html        The site — single file, no build step
images/
  medals.png      The full medal group
  mc-citation.png The original W.3121 recommendation (TNA: WO 373/9)
README.md
.nojekyll         Tells GitHub Pages to serve the files as-is
```

## Deploying to GitHub Pages

1. Create a GitHub account if you don't have one.
2. Create a new **public** repository — e.g. `patrick-leatham`.
3. From the site directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/patrick-leatham.git
   git push -u origin main
   ```
4. In the repository on GitHub, go to **Settings → Pages**.
5. Under **Source**, select **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
6. Wait 1–2 minutes. The site will be live at:
   ```
   https://YOUR-USERNAME.github.io/patrick-leatham/
   ```

## Custom domain (optional)

If you want something like `patrickleatham.co.uk`:
1. Buy the domain (Namecheap, Gandi, Cloudflare Registrar, etc. — £10–15/year).
2. Add a `CNAME` file to this repo containing just the domain name.
3. Configure the DNS records per [GitHub's custom-domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Licence

Content is for family and personal tribute use. Images of the medals and of the W.3121 recommendation are family papers, shared here in memory. The Mercer article linked from the site is © *Military History Matters* and is cited, not reproduced.
