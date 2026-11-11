# LJT-Homepage

Personal academic homepage of **Junteng Liu**, a first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology (HKUST). His research focuses on natural language processing and machine learning.

This site is built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template, forked from [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io) and customized with his own content.

## Site content

- **About (home page)** — personal details, research interests and skills, education, research experience, publications, awards and honors, and contact information (`_pages/about.md`).
- **Publications** — the full publication list (`_pages/publications.html`), rendered from the entries in `_publications/`. The same publication list is also included on the About page.

## Configuration

Site-wide settings (name, bio, email, GitHub, Google Scholar, X, navigation) are defined in `_config.yml` and `_data/navigation.yml`.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000 in your browser.
