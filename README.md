# StopPic site

Landing page for [StopPic](https://github.com/paymepain/stoppic). Plain HTML and CSS, no build step and no scripts.

- `index.html`: English page, `/`
- `ru/index.html`: Russian page, `/ru/`
- `assets/style.css`: shared styles
- `assets/og-source.html`: source of the social image `assets/og.png`

The site uses root-relative links, so it must be served from a domain root. Published on GitHub Pages from a repository named `paymepain.github.io`.

Preview locally: `npx serve .` or `python -m http.server`, not by opening the file directly.

When changing page text, update both languages.
