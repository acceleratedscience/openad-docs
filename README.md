# OpenAD Documentation

This repo contains the documentation website for OpenAD, which can be viewed at:

[acceleratedscience.github.io/openad-docs](https://acceleratedscience.github.io/openad-docs/)

It is built using [just-the-docs](https://github.com/just-the-docs/just-the-docs) which runs on [Jekyll]. More instructions regarding just-the-docs can be found in the [just-the-docs README].

<br>

## Build &amp; Preview Locally

Assuming [Jekyll] and [Bundler] are installed on your computer:

1.  Change your working directory to the root directory of your site.

1.  Run `bundle install`.

1.  Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

    The built site is stored in the directory `_site`.

<br>

## Update Live Website

The website is automatically redeployed whenever the `main` branch is updated.

    git add .
    git commit -m "Updated documentation"
    git push

Deployment is managed by GitHub Actions, more information about this in the [just-the-docs README].

[Jekyll]: https://jekyllrb.com
[Bundler]: https://bundler.io
[just-the-docs README]: README-just-the-docs.md
