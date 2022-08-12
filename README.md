# Mkdocs Template

This template is useful for building the documentations for your McGill-NLP project. It uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). You can start by editing the content in `docs/`. If you need to edit the configurations and/or deploy mkdocs, start with the official [Getting Started](https://squidfunk.github.io/mkdocs-material/getting-started/).

## Alternatives

If you are planning to have a main website for your project as well as documentation, it's recommended to use the [`project-page-template`](https://github.com/McGill-NLP/project-page-template) for both, as you would only need to maintain a single repository and use a single framework (i.e. minimal-mistake/Jekyll).

## Instructions

- Edit Title: go to `mkdocs.yml` and change the `site_name` field.
- Edit GitHub URL in the Footer: go to `mkdocs.yml` and change the `extra > social` field.
- Deploy: Go to Settings > Pages > Source: Deploy from a branch, then select the `gh-pages`. That branch is automatically generated when you push to the `main` branch via a [workflow](./.github/workflows/mkdocs.yml), so do not edit that branch directly! Make any required changes to `/docs` then push to `main`.