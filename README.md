# cnogola.github.io

Personal site and blog for [Gonçalo Lourenço](https://github.com/cnogola) — about software testing, a CV, and occasional posts. The live site is at **[https://cnogola.github.io](https://cnogola.github.io)**.

## Stack

- **[Jekyll](https://jekyllrb.com/)** static site generator
- **[Minima](https://github.com/jekyll/minima)** theme
- **[GitHub Pages](https://pages.github.com/)** via the `github-pages` gem (keeps local builds aligned with GitHub’s Jekyll)
- Plugins: `jekyll-feed`, `jekyll-paginate-v2`

## Local development

**Requirements:** Ruby and [Bundler](https://bundler.io/).

```bash
bundle install
bundle exec jekyll serve
```

Then open the URL Jekyll prints (usually `http://127.0.0.1:4000`).

If you change `_config.yml`, restart the server so changes apply.

## Repository layout

| Path | Purpose |
|------|--------|
| `_config.yml` | Site title, theme, plugins, navigation, analytics |
| `_layouts/`, `_includes/` | Layout overrides |
| `_posts/` | Blog posts (Markdown) |
| `blog/`, `about.md`, `cv/`, `contacts/` | Main pages |
| `assets/` | Styles (`main.scss`) and images |

The built site is output to `_site/` (gitignored) when you run Jekyll locally.

## License

This project is licensed under the [MIT License](LICENSE).
