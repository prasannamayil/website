# Quick Deployment Guide

## To deploy your changes:

```bash
# Add all changes
git add .

# Commit with a descriptive message
git commit -m "Update website with custom domain and blog"

# Push to the page branch
git push origin page
```

## GitHub Pages Setup:
1. Go to Settings → Pages in your repository
2. Under "Source", select "Deploy from a branch"
3. Choose "page" branch and "/" (root) folder
4. Click Save

Your site will be available at:
- https://[your-github-username].github.io/[repository-name]/ (immediately)
- https://www.prasannamayil.com (after DNS propagation, 24-48 hours)

## Don't forget to:
- Add your CV as `data/CV_Prasanna_Mayilvahanan.pdf`
- Replace placeholder images with actual paper figures 