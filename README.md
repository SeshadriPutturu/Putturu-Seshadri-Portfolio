# Putturu Seshadri — Portfolio

A responsive, static portfolio for showcasing backend engineering, cloud platform, and AI experience. It has no package manager or build step and is published automatically with GitHub Pages.

## Preview locally

Open `index.html` in a browser, or start a local static server from the repository root:

```bash
npx serve .
```

## Publish with GitHub Pages

1. Create a GitHub repository for the portfolio and push these files to its `main` branch.
2. In the repository, go to **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` publishes the site on each push to `main`. The published address appears under **Settings → Pages** and in the deployment workflow run.

If the default branch is not `main`, update the branch listed under `on.push.branches` in the workflow.

## Personalize before publishing

- Review the résumé in `assets/Putturu-Seshadri-Resume.pdf` and replace it whenever the résumé changes.
- Check that the contact address and experience details in `index.html` are current.
- Add verified professional profile links if you want them shown; the portfolio does not invent external profiles.
