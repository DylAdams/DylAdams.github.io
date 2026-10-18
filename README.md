# Dylan Adams — portfolio

Personal portfolio site: a landing page, an about page, and detailed project write-ups.
Plain HTML and CSS, no build step.

## Files

- `index.html` — home page with a card for each project
- `about.html` — bio
- `work/` — one page per project (cesyl, bobbert, record-player, makerspace, linux)
- `projects.html` — old address; redirects to the home page
- `css/style.css` — all styling. Colors are at the top; each project's accent color is set by a `p-…` class
- `images/` — photos, plus the site icon (`favicon-*.png`, `apple-touch-icon.png`; `favicon.ico` is at the top level)
- `Dylan-Adams-Resume.pdf` — the resume behind the “Download my resume” button (website copy, no phone number)

## Preview locally

Open `index.html` in a browser.

## Publish on GitHub Pages

1. Create a repo named `DylAdams.github.io` (that exact name makes it your main site).
2. Push these files to the `main` branch.
3. In the repo, go to **Settings → Pages** and set the source to **Deploy from a branch → main → / (root)**.
4. The site goes live at `https://dyladams.github.io` within a minute or two.

If you'd rather use a different repo name (e.g. `portfolio`), it will live at
`https://dyladams.github.io/portfolio/` instead; all links here are relative, so it works either way.
