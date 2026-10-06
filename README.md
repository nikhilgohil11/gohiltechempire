# Gohil Tech Empire — Official Website

Static website for gohiltechempire.com — built with plain HTML, CSS, and JavaScript.
No build step required. Open index.html in any browser.

## Deploy to GitHub Pages

1. Push all files to a public GitHub repository (e.g., `gohiltechempire`)
2. Go to the repository Settings → Pages
3. Source: Deploy from branch → main → / (root) → Save
4. GitHub will provide a URL like `https://yourusername.github.io/gohiltechempire`

## Add Custom Domain (gohiltechempire.com)

1. Create a file named `CNAME` in the repo root containing exactly: `gohiltechempire.com`
2. In your domain registrar's DNS settings, add:
   - A record: `@` → `185.199.108.153`
   - A record: `@` → `185.199.109.153`
   - A record: `@` → `185.199.110.153`
   - A record: `@` → `185.199.111.153`
   - CNAME: `www` → `yourusername.github.io`
3. In GitHub Pages settings, enter `gohiltechempire.com` as the custom domain
4. Check "Enforce HTTPS" once the certificate provisions (10–30 min)

## Local Preview

```bash
# No server needed — just open the file:
open index.html
# Or on Windows:
start index.html
```

## Update Content

All content is in `index.html`. Edit the text directly.
Contact email: `gohil@gohiltechempire.com`
