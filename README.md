# matthewlanger.github.io

This repository holds a Jekyll-based GitHub Pages site for Matthew Langer. I updated the site to use the `jekyll-theme-minimal` theme and added visible social links in the header and footer.

What I added:

- _config.yml — site configuration (theme, social links, email)
- _layouts/default.html — custom layout that shows links visibly in header/footer
- index.md — home page (Markdown) using the custom layout

How to edit:

- Edit files directly on GitHub (web) or clone the repo locally:

  git clone https://github.com/matthewlanger-dev/matthewlanger.github.io.git
  cd matthewlanger.github.io
  # edit files, then:
  git add .
  git commit -m "Update site"
  git push

Publishing / preview:

- For a user site the Pages URL will be: https://matthewlanger-dev.github.io
- GitHub Pages will build the site using Jekyll. Builds typically finish in a few minutes after pushing.

Next recommended steps:

- Optionally remove or replace the custom _layouts/default.html if you prefer the pure theme layout.
- Add images to `assets/` and reference them from the Markdown pages.
- Add a CNAME for a custom domain if desired.
