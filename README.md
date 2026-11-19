# luumsk.github.io

Personal website of **Luu Minh Sao Khue** — AI Research Engineer.

🌐 Live site: [https://luumsk.github.io](https://luumsk.github.io)

## Updating the site

- **News:** add an entry at the top of [`_data/news.yml`](_data/news.yml).
- **Blog post:** copy [`_drafts/paper-explainer-template.md`](_drafts/paper-explainer-template.md) to `_posts/YYYY-MM-DD-short-title.md`, write it, commit and push. Images go in `assets/img/posts/`. The Blog section and nav link appear automatically once the first post exists.
- **Google Scholar:** set `scholar_url` in [`_config.yml`](_config.yml).
- **Preview locally (Docker):**
  `docker run --rm -p 4000:4000 -v "$PWD":/srv/jekyll jekyll/jekyll:3.8 sh -c "gem install jekyll-feed jekyll-seo-tag && jekyll serve --host 0.0.0.0"` → http://localhost:4000
