# Burmese Thinking Machine — website

Live at **https://burmesethinkingmachine.com** (also reachable as www.). Static site, no build step: every file here is served as-is.

## Hosting
- GitHub Pages, branch `main`, root. `CNAME` holds the custom domain — do not delete it.
- DNS at Porkbun: `ALIAS` root → `kelvinmyanmarhan.github.io`, `CNAME www` → `kelvinmyanmarhan.github.io`.
- "Enforce HTTPS" is on in Settings → Pages.

## Updating
- New post: add one `<li class="glass post">` block at the top of the list under `id="panel-mm"` in index.html.
- After Nov 21: replace the disabled download button in the book section with a link to the PDF.
- `og:url` and `og:image` point at the custom domain; keep them in step if the domain ever changes.
