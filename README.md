# Wei Xiong

Personal website: https://weixiongml-bot.github.io/

Built with [al-folio](https://github.com/alshedivat/al-folio). The main branch contains the editable Jekyll source; the gh-pages branch contains the compiled website served by GitHub Pages.

## Update content

- Home: `_pages/about.md`
- Blog: `_pages/blog.md`
- Misc.: `_pages/misc.md`
- CV: `assets/pdf/cv.pdf`
- Contact links: `_data/socials.yml`

## Build

Use Ruby 3.3 and Node.js, then run:

```sh
bundle install
npm ci
bundle exec jekyll build
```

The generated site is in `_site/`. Publish the contents of that folder, including `.nojekyll`, to the `gh-pages` branch. GitHub Pages is configured to serve the root of that branch.

The original al-folio license is included in `LICENSE`.
