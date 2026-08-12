# Suliang Jin — personal academic website

Built from [sbryngelson/academic-website-template](https://github.com/sbryngelson/academic-website-template) (Jekyll).

## TODO before this is ready to share
- [ ] `_config.yml` — real email, GitHub/LinkedIn/Scholar links, CV PDF
- [ ] `images/headshot.svg` — replace placeholder avatar with a real photo (e.g. `images/headshot.jpg`, then update `photo:` in `_config.yml`)
- [ ] `_pages/home.md` — fill in the "About me" paragraph
- [ ] `_pages/about.md` — fill in education and bio
- [ ] `_pages/research.md` — fill in each research area description
- [ ] `assets/ref.bib` — add publications (BibTeX), if any

## Preview locally
Requires [Jekyll](https://jekyllrb.com/docs/installation/):
```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Deploy
Push to `main` on GitHub — the included GitHub Actions workflow (`.github/workflows/deploy.yml`) builds and publishes automatically. Make sure **Settings > Pages > Source** is set to **GitHub Actions**.

Live at: https://Suliang-Jin.github.io/
