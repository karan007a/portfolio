# karanagarwal.com

Personal portfolio site built with Jekyll 4, deployed to GitHub Pages via GitHub Actions.

## Local Development

```sh
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000/

## Structure

```
_config.yml          # Site settings
_layouts/default.html # HTML layout
_data/
  projects.yml       # Featured projects
  skills.yml         # Skills by category
  experience.yml     # Work experience timeline
  social.yml         # Social/contact links
assets/css/style.css  # Styles
index.html            # Main page
CNAME                 # Custom domain
```

## Deployment

Pushes to `main` trigger the GitHub Actions workflow which builds and deploys to GitHub Pages.

Custom domain: https://karanagarwal.com
