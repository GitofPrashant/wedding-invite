# Tejaswini & Aviral · Wedding Invitation

A static site: no build step. Upload this whole folder as-is.

## GitHub Pages
1. Create a public repo (e.g. `wedding-invite`) and upload every file in this folder, including `.nojekyll`.
2. Repo → Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<username>.github.io/wedding-invite/`.

## Netlify
Drag this folder onto https://app.netlify.com/drop.

## Vercel
`npx vercel` inside this folder (framework preset: Other).

Note: open the hosted link, not the downloaded file. Phones don't run pages opened from Downloads or WhatsApp attachments.
