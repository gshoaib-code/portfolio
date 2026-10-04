# Ghaniya Shoaib portfolio

Static site: `index.html` (all pages, hash routes), `404.html`, `vercel.json`, `assets/docs/` (resume + recommendation letter).

## Deploy on Vercel
1. Create a GitHub repo and push this folder (github.com > New repository > upload files).
2. vercel.com > Add New > Project > import the repo. Framework preset "Other", no build command, output directory blank. Deploy.
3. Every push to GitHub redeploys automatically; other branches get preview URLs.

## Contact form
Create a free form at formspree.io, copy the ID from `https://formspree.io/f/XXXX`, and replace `FORM_ID` in the script at the bottom of `index.html`. Send one test message from the live site.

## Tokens
Colours, type scale and spacing are CSS custom properties at the top of `index.html` (Light and Dark).

## Before sharing
Replace every `[ADD: ...]` placeholder. Confirm the recommendation letter may be public. Vercel Hobby is for personal, non-commercial use; check vercel.com/pricing.
