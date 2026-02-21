<!-- badges: start -->
📦 [Repo](https://github.com/microbiome/OMA-extras) [![rworkflows](https://img.shields.io/github/actions/workflow/status/microbiome/OMA-extras/rworkflows.yml?label=Package%20check)](https://github.com/microbiome/OMA-extras/actions/workflows/rworkflows.yml)
📖 [Book](https://microbiome.github.io/OMA-extras/) [![deployment](https://img.shields.io/github/actions/workflow/status/microbiome/OMA-extras/pages/pages-build-deployment?label=Book%20deployment)](https://github.com/microbiome/OMA-extras/actions/workflows/pages/pages-build-deployment)
🐳 [Docker](https://github.com/microbiome/OMA-extras/pkgs/container/OMA-extras) [![biocbook](https://img.shields.io/github/actions/workflow/status/microbiome/OMA-extras/biocbook.yml?label=Docker%20image)](https://github.com/microbiome/OMA-extras/actions/workflows/biocbook.yml)
<!-- badges: end -->

**README from [microbiome/OMA-extras](https://github.com/microbiome/OMA-extras)**

# Orchestrating Microbiome Analysis Book — extras <img src="inst/assets/mia_logo.png" align="right" width="120" />

## Overview

This is a reference cookbook for performing **Microbiome Analysis** with
Bioconductor in R. This book is based on Quarto and **`BiocBook`**
(<https://www.bioconductor.org/packages/release/bioc/html/BiocBook.html>).

## Funding

<img src="inst/assets/findingpheno_logo.png" align="right" width="160" />

This project received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 952914 ([FindingPheno](https://findingpheno.eu/)).


## Deployment

The book release version is automatically built and deployed from the 
`devel` branch to the `gh-pages` branch using GitHub Actions.

You can also preview it locally after _cloning_ this Github
repository. This is useful if you want to suggest
improvements to the material. You can also use this to test the build
before making a pull request to add your new changes to the official
release.

Building and viewing the book locally involves the following steps:

1. Install the necessary dependencies to build to book:

```
BiocManager::install(remotes::local_package_deps(dependencies=TRUE))
devtools::install('.')
```

2. Render and view the book:

```
BiocBook::preview(BiocBook::BiocBook('.'))
```

# Code of conduct

Please note that the OMA project is released with a
[Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
