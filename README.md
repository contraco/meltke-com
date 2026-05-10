# meltke.com — Frank Meltke Personal Entity Home

## Setup Checklist

### 1. GitHub Secrets (Settings → Secrets → Actions)
Add these two secrets — same values as used in contraco repos:
- `INDEXNOW_KEY` → `60c9437e711e49a7b6edea770cc55f90`
- `GH_PAT` → your existing Personal Access Token

### 2. Copy Favicon Assets from contraco-net repo
Copy these files from `contraco/` into this repo root:
```
favicon-16x16.png
favicon-32x32.png
favicon-96x96.png
apple-touch-icon.png
apple-touch-icon-precomposed.png
apple-touch-icon-57x57.png
apple-touch-icon-60x60.png
apple-touch-icon-72x72.png
apple-touch-icon-76x76.png
apple-touch-icon-114x114.png
apple-touch-icon-120x120.png
apple-touch-icon-144x144.png
apple-touch-icon-152x152.png
apple-touch-icon-180x180.png
android-icon-36x36.png
android-icon-48x48.png
android-icon-72x72.png
android-icon-96x96.png
android-icon-144x144.png
android-icon-192x192.png
ms-icon-70x70.png
ms-icon-144x144.png
ms-icon-150x150.png
ms-icon-310x310.png
```

### 3. Goatcounter
Register `meltke` as a new site at goatcounter.com
The counter is already wired in index.html as:
`https://meltke.goatcounter.com/count`

### 4. DNS Settings (after repo is public + GitHub Pages enabled)
Add these DNS records at your registrar:
```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  Frank-Meltke.github.io
```

### 5. GitHub Pages
Settings → Pages → Source: Deploy from branch `main` / root

### 6. IndexNow Key
File `60c9437e711e49a7b6edea770cc55f90.txt` is already in repo root.
Verify live at: https://meltke.com/60c9437e711e49a7b6edea770cc55f90.txt

### 7. Google Search Console
Already verified (sc-domain:meltke.com is in your GSC).
After DNS is live → Request Indexing for https://meltke.com/

### 8. Wikidata Updates (after site is live)
- Q139680598 (Frank Meltke): promote meltke.com to primary official website
- Q139681815 (contraco): fill French/German/Russian descriptions
