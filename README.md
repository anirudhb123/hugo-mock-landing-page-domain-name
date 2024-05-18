# hugo-mock-landing-page-autodeployed

CIS 3500 HW2 Part III

This repository hosts a mock landing page built with Hugo at https://mydomain.hair, automatically deployed to GitHub Pages using GitHub Actions.

## Workflow Description

The workflow defined in this repository automates the process of building and deploying the Hugo static website to GitHub Pages. Here's an overview of the workflow:

1. **Check Out Source Repository**: This step checks out the source repository, including any submodules.
2. **Initialize Hugo Environment**: Sets up the Hugo environment with the specified version and flags.
3. **Compile Hugo Static Files**: Compiles the Hugo static files, including drafts, for deployment.
4. **Publish to GitHub Pages**: Publishes the compiled static files to the `gh-pages` branch, making the website live on GitHub Pages.

The workflow is triggered on each push to the `main` branch.
