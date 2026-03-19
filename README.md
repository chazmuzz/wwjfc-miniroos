# WWJFC MiniRoos website

This repository hosts the GitHub Pages website for Warilla Wanderers Junior Football Club MiniRoos information and documentation.

## Site approach

- Jekyll site built for GitHub Pages.
- Markdown-first pages for simple updates.
- One canonical MiniRoos programme page, with shorter audience pages for parents, coaches and volunteers.
- Minimal styling and one local image asset: the club badge.

## Main content files

- `index.md` - site landing page
- `programme.md` - main MiniRoos programme reference
- `parents.md` - parent-focused guidance
- `coaches.md` - coach-focused guidance
- `volunteers.md` - volunteer guidance
- `faq.md` - common questions

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open the local address Jekyll prints in the terminal.

## Publishing

This repo is intended for GitHub Pages. Keep the site GitHub Pages compatible by avoiding unsupported plugins and keeping the build simple.
