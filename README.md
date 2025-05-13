# Future of Multimodal AI Presentation

Presentation slides for the Future of Multimodal AI talk at InfoBib conference.

## Viewing the Presentation

This presentation is deployed to GitHub Pages and is available at the following URL:

[https://stefania11.github.io/future_multimodal_ai/](https://stefania11.github.io/future_multimodal_ai/)

## Deployment Instructions

### Automatic Deployment

The presentation automatically deploys to GitHub Pages when changes are pushed to the `main` branch using a GitHub Actions workflow. The workflow file is located at `.github/workflows/deploy.yml`.

When you push changes to the main branch, the GitHub Actions workflow will:
1. Check out the repository
2. Configure GitHub Pages
3. Upload the presentation files
4. Deploy to GitHub Pages

### Manual Deployment

To manually trigger deployment without pushing changes (e.g., if you want to redeploy the current version):

```bash
# Using GitHub CLI
git checkout main
gh workflow run deploy.yml

# Check deployment status
gh run list --workflow=deploy.yml --limit 1
```

The deployment typically completes within 1-2 minutes.

## Deployment Status

The presentation is deployed using GitHub Actions workflow. The repository is public to enable GitHub Pages deployment.

## Local Development

To view the presentation locally, simply open `index.html` or `presentation.html` in your web browser.
