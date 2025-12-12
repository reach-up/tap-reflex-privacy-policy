# GitHub Pages Setup Instructions

This repository is now ready to be published as a GitHub Pages site.

## How to Enable GitHub Pages

1. Go to your GitHub repository: https://github.com/reach-up/tap-reflex-privacy-policy
2. Click on **Settings** (top menu)
3. In the left sidebar, click on **Pages** (under "Code and automation")
4. Under "Build and deployment":
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select `copilot/publish-github-pages` and `/ (root)` folder
   - Click **Save**

5. GitHub will start building your site. This may take a few minutes.
6. Once deployed, your site will be available at:
   - `https://reach-up.github.io/tap-reflex-privacy-policy/`

## Files Created

- `index.html` - The main privacy policy page with clean styling
- `_config.yml` - Jekyll configuration file with theme and metadata
- `GITHUB_PAGES_SETUP.md` - This documentation file

## Updating the Privacy Policy

To update the privacy policy content:
1. Edit the `index.html` file
2. Modify the content within the `<div class="container">` section
3. Commit and push your changes
4. GitHub Pages will automatically rebuild and deploy your site

## Alternative: Using README.md

If you prefer to use the existing `README.md` file instead of `index.html`:
1. Rename or delete `index.html`
2. Update `README.md` with your privacy policy content in Markdown format
3. GitHub Pages will automatically render the README as the index page using Jekyll

## Testing Locally (Optional)

To test the site locally before publishing:

```bash
# Install Ruby and Jekyll (if not already installed)
# Visit https://jekyllrb.com/docs/installation/

# Run Jekyll server
jekyll serve

# Visit http://localhost:4000 in your browser
```
