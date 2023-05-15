# doc-test Docs

doc-test

## How it works

Backstage uses `docs-like-code` approach for software documentation. Engineers write their documentation in Markdown files which live together with their code - and with little configuration get a nice-looking doc site in Backstage.

## Managing the docs
The template bootstraps a simple Backstage documentation skeleton. Please see `docs/index.md` for a how-to work with the docs.

## Publishing changes
The template also bootstraps a .gitlab-ci.yml-file which generates and publishes the docs to the central Intility Backstage object storage. To update your documentation:

1. Update the files under `docs`.
2. Merge your changes to the `main` branch. The pipeline will generate/build the docs for all branches, but only publish in the main branch. 

Please see the [official Backstage doc for architecture overview](https://backstage.io/docs/features/techdocs/architecture#recommended-deployment) for more information.