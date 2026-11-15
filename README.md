# Burmese Thinking Machine — website

Static site. No build step: every file here is served as-is.

## Put it online with GitHub Pages
1. Create a free GitHub account at github.com (use your own personal email).
2. New repository → name it `<your-username>.github.io` → Public → Create.
3. "uploading an existing file" → drag in everything from this folder (index.html, the assets folder, .nojekyll) → Commit changes.
4. Wait 1–2 minutes, then open `https://<your-username>.github.io`.

## Add your own domain later
Repository → Settings → Pages → Custom domain → type the domain → Save, then add the DNS records GitHub shows at your registrar. Turn on "Enforce HTTPS" when it becomes available.

## Updating
- New post: add one `<li class="glass post">` block at the top of the list under `id="panel-mm"` in index.html.
- After Nov 21: replace the disabled download button in the book section with a link to the PDF.
