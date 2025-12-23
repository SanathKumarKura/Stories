# Stories

A simple Jekyll blog starter. This repository contains the minimal files to publish a blog using GitHub Pages and the Jekyll `minima` theme.

How to publish:
1. Create a repository on GitHub named `Stories`.
2. Push the files in this repo to the `main` branch.
3. Go to the repository Settings → Pages and set the source to the `main` branch and `/ (root)`.
4. Wait a minute — GitHub Pages will build the site using Jekyll and the `minima` theme.

To create a new post:
- Add a markdown file under `_posts/` with the filename format `YYYY-MM-DD-title.md`.
- Use YAML front matter with `layout: post`, `title`, and `date`.

Local development:
- Install dependencies: `bundle install` (requires Ruby and Bundler).
- Serve locally: `bundle exec jekyll serve` and open `http://localhost:4000`.
