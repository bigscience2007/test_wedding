# Our Wedding Website

A single-page wedding website (`index.html`) — no build step, no dependencies.

## Before you publish

The content is currently placeholder text ("Alex & Jordan", fake venue/date/schedule/wedding party). Edit `index.html` directly and swap in your real details.

RSVP: the RSVP section links to `PASTE_GOOGLE_FORM_URL_HERE` — replace that with your actual Google Form share link (Google Forms → **Send** → link icon → copy). To embed the form on the page instead of linking out, swap the `<a>` for an `<iframe src="YOUR_FORM_EMBED_URL">` (Send → embed icon `<>`).

## Publishing with GitHub Pages

1. Push this repo to GitHub (see below).
2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the `main` branch and `/ (root)` folder, then **Save**.
5. Your site will be live at `https://bigscience2007.github.io/test_wedding/` within a minute or two.

## Pushing this repo

```
git remote add origin https://github.com/bigscience2007/test_wedding.git
git push -u origin main
```
