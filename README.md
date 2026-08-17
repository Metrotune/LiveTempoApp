# LiveTempoApp landing page

Static site. Deploy to GitHub Pages:

1. Push these files to a repo (index.html at the repo root, or in /docs).
2. Repo Settings -> Pages -> Source: Deploy from a branch -> main -> / (root).
3. Before publishing, replace the placeholder App Store link: `http://no/linkyet`
   appears three times in index.html (header button, hero button, closing button).

No build step, no dependencies. The font (Space Grotesk) loads from Google Fonts;
delete that <link> and the font-family on .lt-page if you want zero external requests.
