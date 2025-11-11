# GitHub Pages Setup Guide

This repository is configured to use Jekyll with GitHub Pages. Follow these steps to enable GitHub Pages for your site.

## Setup Steps

### 1. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** (or **master**) as the branch
6. Select **/ (root)** as the folder
7. Click **Save**

### 2. GitHub Pages will automatically:
- Build your Jekyll site
- Make it available at: `https://[username].github.io/Team-O-Matic-2025/`
- Rebuild automatically when you push changes to the main branch

## Local Development (Optional)

If you want to test the site locally before pushing:

### Prerequisites
- Ruby (version 2.5 or higher)
- Bundler gem

### Setup
1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build and serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser to `http://localhost:4000`

## Site Structure

- `_config.yml` - Jekyll configuration
- `index.md` - Homepage
- `_layouts/` - Layout templates
- `_includes/` - Reusable components (header, footer, head)
- `assets/` - CSS and other static assets
- `*.md` - Content pages (all documentation files)

## Navigation

The site navigation is configured in `_config.yml` under `header_pages`. All pages listed there will appear in the navigation menu.

## Customization

- **Styling**: Edit `assets/css/custom.css` to customize the appearance
- **Layout**: Modify files in `_layouts/` and `_includes/` to change the site structure
- **Content**: Edit the `.md` files to update page content

## Notes

- GitHub Pages uses Jekyll 3.9.0 by default
- The site uses the Minima theme as a base
- All markdown files have Jekyll front matter for proper rendering
- The `README.md` file is excluded from the site (as configured in `_config.yml`)

## Troubleshooting

If the site doesn't build:
1. Check the GitHub Actions tab for build errors
2. Verify all files have proper front matter (YAML headers)
3. Ensure `_config.yml` is valid YAML
4. Check that all linked pages exist

