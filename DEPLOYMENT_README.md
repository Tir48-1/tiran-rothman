# Tiran Rothman website — v31 production

This package is designed as a complete replacement for the GitHub Pages repository root.

## Deploy
1. Back up the current repository.
2. Replace the repository contents with the contents of this package.
3. Keep `CNAME` as `tiranrothman.com`.
4. Commit to the branch used by GitHub Pages.
5. Verify `/`, `/he/`, `/startup-valuation/`, `/behavioral-finance/`, `/research/`, `/expert-opinions/`, `/speaking/`, `/book/`, `/insights/`, `/robots.txt`, `/sitemap.xml`, and `/llms.txt`.
6. In Google Search Console submit `https://tiranrothman.com/sitemap.xml` and request indexing for the homepage and main topic pages.
7. In Bing Webmaster Tools submit the sitemap as well.

## v31 changes
- Fully local portrait and social image; no GitHub Raw dependency.
- Complete asset package.
- Mobile-first breakpoints and accessible navigation.
- Larger, clearer organization logos.
- Shared CSS/JS to reduce duplication.
- Stronger canonical entity block and structured data.
- Expanded first-party topic pages for behavioral finance, valuation, research, expert opinions, speaking, book and insights.
- Static Hebrew profile page.
- Updated robots, sitemap, llms files, 404 page and web manifest.


## v31.1 entity verification
- Springer book source: https://link.springer.com/book/10.1007/978-3-030-38847-8
- TheMarker 40 Under 40 (2018): https://www.themarker.com/magazine/2018-11-05/ty-article-static/0000017f-db7f-d856-a37f-ffff00760000
- Springer book URL is intentionally attached to the Book entity, not Person.sameAs.

## v31.2 visual fix
- Uses real full-color organization logos from verified public sources with local fallbacks.
- Removes grayscale filtering and increases logo display size.
- Fixes TheMarker 40 Under 40 metric overlap.
