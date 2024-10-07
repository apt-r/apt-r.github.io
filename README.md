# apt-r.github.io

![Quarto Publish](https://github.com/apt-r/apt-r.github.io/actions/workflows/quarto-publish.yml/badge.svg)

![Pages Build Deployment](https://github.com/apt-r/apt-r.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)

This is the repository for the [apt-r](https://apt-r.github.io) website. It is built using [Quarto](https://quarto.org) and hosted on GitHub Pages.

The source files for the website are commited to the `main` branch and the built website (what you see at [apt-r.github.io](https://apt-r.github.io)) is commited to the `gh-pages` branch.

You should _not_ commit directly to the `gh-pages` branch. Instead, make changes to the source files in the `main` branch and let [this GitHub Action workflow](.github/workflows/quarto-publish.yml) build the website and push the changes to the `gh-pages` branch.
