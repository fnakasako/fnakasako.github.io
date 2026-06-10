# fnakasako.github.io

Personal site, published via GitHub Pages at https://fnakasako.github.io.

Plain HTML/CSS — no build step, no generator.

## Structure

- `index.html` — homepage (about, research, projects, writing, contact)
- `style.css` — single shared stylesheet
- `writing/index.html` — post index
- `writing/hello-world.html` — first post; copy it as the template for new posts

## Adding a post

1. Copy `writing/hello-world.html` to `writing/<slug>.html`
2. Update title, `<time>` date, and content
3. Add the post to `writing/index.html` and the Writing section in `index.html`
4. Commit and push — Pages deploys automatically

Posts include KaTeX via CDN for math; delete that `<head>` block in posts that don't need it.
