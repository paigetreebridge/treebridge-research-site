# Treebridge Research

Static site. No build step.

```
index.html      the site
images/         photos, wordmark background, favicon
CNAME           custom domain (treebridgeresearch.io)
.nojekyll       serve files as-is
```

## Deploy
1. New GitHub repo. Upload everything in this folder to the repo root.
2. Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
3. Live at https://<user>.github.io/<repo>/ within a minute.

## Custom domain
DNS: A records for treebridgeresearch.io → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME www → <user>.github.io.
Settings → Pages → Custom domain: treebridgeresearch.io → Enforce HTTPS. Delete the CNAME file if not using the domain.

## Editing
Copy is plain HTML in index.html. Colors: CSS variables at the top of the style block; highlight #FF005D. Fonts (Bungee, Tanker, IBM Plex Mono) load from Google Fonts and Fontshare.
