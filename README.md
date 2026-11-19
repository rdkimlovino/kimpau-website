# kimpau.com

Family blog for Kim & Paula Lovino — Lia, Oriana and Quea.
YouTube + Instagram: @kimpauever

Monetization: ads + affiliate links. See /affiliate-disclosure/.

## How posting works

1. Kim tells Muse the post idea (or picks one from the content plan).
2. Muse drafts the post, with title, keyword, honest recommendations, and affiliate links clearly disclosed.
3. Kim approves the exact draft.
4. Muse adds a new folder under `blog/<slug>/index.html`, adds it to `blog/index.html` and `sitemap.xml`, and pushes to GitHub.
5. Cloudflare Pages auto-deploys on push to `main`. The post is live at `https://kimpau.com/blog/<slug>/` within a minute or two.
6. Muse verifies the live URL (HTTP 200, correct title/H1) and reports back.

No WordPress login, no editor. Posts are files in this repo.

## Structure

- `index.html` — homepage
- `blog/index.html` — blog hub
- `blog/<slug>/index.html` — one post per folder
- `about/index.html`
- `affiliate-disclosure/index.html`
- `privacy-policy/index.html`
- `sitemap.xml`, `robots.txt`

## Hosting

GitHub repo: rdkimlovino/kimpau-website (public, branch main)
Cloudflare Pages: kimpau-website — kimpau-website.pages.dev
Custom domains: kimpau.com + www.kimpau.com
