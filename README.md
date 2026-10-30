# tien-chen-lin.github.io

Personal academic website of **Dr. Tien-Chen Lin** — how developing neurons establish durable axonal and dendritic identities while their cytoskeleton remains dynamic.

*Updated 30 October 2026: research content aligned with the October IMB plan and Constitution v0.5; visual design and documented independence/mentoring evidence revised. See [revision notes](docs/WEBSITE_UPDATE_2026-10-30.md).*

Live site: https://tien-chen-lin.github.io

> Research code lives separately at [github.com/darkbreaker0](https://github.com/darkbreaker0) — including the repositories cited in the Nature (2026) paper.

## Built with
- [Jekyll](https://jekyllrb.com/) + Jekyll Scholar, on a customized fork of the
  [academic-website-template](https://github.com/sbryngelson/academic-website-template).
- Deployed automatically by GitHub Actions on every push to the `source` branch.

## Local development
```bash
bundle install
bundle exec jekyll serve   # then open http://localhost:4000
```

## Editing content
- Identity, links, accent colour, navigation: `_config.yml`
- Profile (education, honours, mentees): `_data/pi.yml`, `_data/awards.yml`, `_data/people.yml`
- News: `_data/news.yml`
- Publications: `assets/ref.bib`
- Pages: `_pages/*.md`
