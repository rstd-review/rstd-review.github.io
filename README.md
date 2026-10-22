# RSTD Review — Project Website

Project page for **A Comprehensive Review of Remote Sensing Target Detection: From Data and Models to Applications**.

> **Status:** The manuscript is in preparation. The website currently contains draft descriptions and a provisional review structure. The abstract, taxonomy, comparisons, author details, and publication information will be updated to match the final manuscript.

## Intended website

https://rstd-review.github.io/

## Intended repository

https://github.com/rstd-review/rstd-review.github.io

## Files

- `index.html` — responsive academic project page; includes styles and lightweight interactions.
- `assets/favicon.svg` — website icon.
- `.github/workflows/pages.yml` — GitHub Actions workflow to deploy the site to GitHub Pages.
- `.nojekyll` — disables Jekyll processing for static assets.

## Publish

1. Create a **public** repository named `rstd-review.github.io` under the GitHub account or organization `rstd-review`.
2. Upload the contents of this ZIP to the **repository root** (so `index.html` is at the root, not inside another folder) and commit them to the `main` branch.
3. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source.
4. Open **Actions** and wait for the deployment workflow to complete successfully.
5. Visit https://rstd-review.github.io/.

## Update after the paper is finished

Edit `index.html` to add the final abstract, author list and affiliations, verified dataset/model coverage, paper PDF, supplementary materials, publication details, and BibTeX. Do not treat the current draft descriptions or citation placeholders as final paper claims.

The website is a static HTML/CSS/JavaScript page. No build step or package installation is required.
