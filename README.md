# Monna’s Daily Journal

A Jekyll-based daily diary template configured for GitHub Pages.

## What you get
- Jekyll structure with `_posts/` for daily Markdown entries.
- Mobile-friendly layout, OG/Twitter meta tags, Light/Dark auto theme.
- Comment system support via **Utterances** (GitHub Issues).
- Placeholder for **Google Analytics (GA4)** — replace the ID.
- `CNAME` already set to monna.cloud — configure your DNS to point to GitHub Pages.

## Quick start
1. Create a new GitHub repository named `YOUR_USERNAME.github.io`.
2. Upload the contents of this project to the repository root and commit.
3. In the repo settings → Pages, ensure branch `main` (or `gh-pages`) is used.
4. Add your GA4 Measurement ID into `_config.yml` (google_analytics).
5. Configure Utterances:
   - Replace `YOUR_GITHUB_USERNAME/REPO` in `_includes/comments.html` with your repo.
6. Set DNS A records for `@` to GitHub Pages and add CNAME for `www` -> monna.cloud.
7. Create a new post: add a Markdown file in `_posts/` with filename `YYYY-MM-DD-title.md` and include image files in `assets/images/`.

## Example post
See `_posts/2025-11-10-day-1.md` as a template — copy, edit, and commit daily.

## Notes
- The site uses the default `minima` theme for simplicity and GitHub Pages compatibility.
- Replace placeholders (GitHub username, GA ID) before going live.
