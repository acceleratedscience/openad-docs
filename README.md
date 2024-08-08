# OpenAD Documentation

This repo contains the documentation website for OpenAD, which can be viewed at:<br>[acceleratedscience.github.io/openad-docs](https://acceleratedscience.github.io/openad-docs/)

<br>

## Updating Documentation

Most of the documentation is auto-generated from the README file in the main [OpenAD repository]:

- commands.md
- installation.md

For instructions on how to regenerate the documentation files, please refer to [/docs/generate_docs.py](https://github.com/acceleratedscience/open-ad-toolkit/blob/main/docs/generate_docs.py) in the OpenAD repo.

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

## Tech Stack

The documentation website is built using [just-the-docs](https://github.com/just-the-docs/just-the-docs) which runs on [Jekyll].<br>
Deployment is managed by GitHub Actions. More information can be found in the [just-the-docs README].

[Jekyll]: https://jekyllrb.com
[Bundler]: https://bundler.io
[just-the-docs README]: README-just-the-docs.md
[OpenAD repository]: https://github.com/acceleratedscience
