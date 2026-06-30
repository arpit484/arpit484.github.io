# Arpit Saxena — Personal Website

A fast, single-file static website. No build step, no server code, no database — it loads instantly and a free CDN host can absorb large traffic spikes smoothly.

## Files
- `index.html` — the entire website (HTML + CSS + JS in one file)
- `assets/Arpit_Saxena_Resume.pdf` — résumé that the "Download CV" buttons serve
- `assets/profile.jpg` — **your photo (add this — see below)**

## 1. Add your photo (1 minute)
Save the headshot you shared as **`profile.jpg`** inside the `assets` folder
(`Career/website/assets/profile.jpg`). A square image (e.g. 600×600) looks best.
Until you add it, the site shows an "AS" monogram automatically — nothing breaks.

## 2. Preview locally
Double-click `index.html` — it opens in your browser. That's the live site.

## 3. Publish it free (pick one)
All three are free, give HTTPS + global CDN, and handle heavy traffic.

**Netlify Drop (easiest, ~2 min)**
1. Go to https://app.netlify.com/drop
2. Drag the whole `website` folder onto the page.
3. You get a live URL instantly (e.g. `arpit-saxena.netlify.app`). Rename it in Site settings.

**Vercel**
1. Install: `npm i -g vercel`
2. In the `website` folder run `vercel` and follow the prompts.

**GitHub Pages**
1. Create a repo, upload the contents of `website` (keep `index.html` at the root).
2. Repo → Settings → Pages → Branch: `main` / root → Save.
3. Live at `https://<username>.github.io/<repo>/`.

## 4. Custom domain (optional)
Buy a domain (e.g. `arpitsaxena.com`) and point it at your host in their domain
settings — each host above has a one-click "Add custom domain" flow.

## Updating
Edit `index.html` text directly, or replace `assets/Arpit_Saxena_Resume.pdf`
with a newer résumé (keep the same filename). Re-upload / redeploy.
