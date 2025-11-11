# GitHub Pages Troubleshooting Guide

## Recent Fixes Applied

1. **Updated `_config.yml` with correct GitHub Pages configuration:**
   - Set `baseurl: "/Team-O-Matic-2025"` (required for project pages)
   - Set `url: "https://dairyking98.github.io"` (your GitHub username)

2. **Fixed markdown links in `index.md`:**
   - Changed to use simple relative paths that Jekyll will process correctly
   - Removed HTML divs that were interfering with markdown processing

3. **Simplified layout structure:**
   - Removed custom layout that was interfering with Minima theme
   - Using Minima's default layout with custom includes for navigation

## If Site Still Not Working

### Check GitHub Pages Build Status

1. Go to your repository on GitHub
2. Click on the **Actions** tab
3. Look for any failed builds or error messages
4. Check the build logs for specific errors

### Verify GitHub Pages Settings

1. Go to **Settings** → **Pages**
2. Ensure **Source** is set to **Deploy from a branch**
3. Select **main** (or **master**) branch
4. Select **/ (root)** folder
5. Click **Save**

### Common Issues and Solutions

#### Issue: Markdown not rendering
- **Solution:** Ensure `_config.yml` has `markdown: kramdown` (already set)
- Check that files have proper front matter (YAML headers)
- Verify layout is set to `default` in page front matter

#### Issue: CSS not loading
- **Solution:** Check that `assets/main.scss` exists and imports Minima
- Verify `_includes/head.html` links to the correct stylesheets
- Clear browser cache and hard refresh (Ctrl+F5)

#### Issue: Links not working
- **Solution:** With baseurl set, Jekyll should handle paths automatically
- Verify permalinks in front matter are correct (already verified)
- Links should work with relative paths like `PROJECT_DESCRIPTION.html`

#### Issue: Navigation not showing
- **Solution:** Verify `header_pages` in `_config.yml` lists all page files
- Check that `_includes/header.html` exists and is correct
- Ensure pages have `title` in front matter

### Testing Locally (Optional)

If you want to test the site locally before pushing:

```bash
# Install dependencies
bundle install

# Build and serve locally
bundle exec jekyll serve

# Open http://localhost:4000/Team-O-Matic-2025/
```

### Expected Site URL

Your site should be available at:
**https://dairyking98.github.io/Team-O-Matic-2025/**

Note: It may take a few minutes after pushing changes for GitHub Pages to rebuild the site.

### Next Steps

1. Commit and push these changes to GitHub
2. Wait 2-5 minutes for GitHub Pages to rebuild
3. Check the Actions tab for build status
4. Visit your site URL to verify it's working
5. If issues persist, check the build logs in the Actions tab

