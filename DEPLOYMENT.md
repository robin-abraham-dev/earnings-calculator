# GitHub Pages Deployment Guide

This guide will help you deploy the Business Partner Earnings Calculator to GitHub Pages.

## Prerequisites

- A GitHub account
- Git installed on your local machine

## Step-by-Step Deployment

### 1. Create a New Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `earnings-calculator` or `business-partner-calculator`)
5. Make sure it's set to **Public** (required for free GitHub Pages)
6. Don't initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

### 2. Upload Files to GitHub

#### Option A: Using GitHub Web Interface

1. In your new repository, click "uploading an existing file"
2. Drag and drop all the files from this project:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Add a commit message like "Initial commit: Add earnings calculator"
4. Click "Commit changes"

#### Option B: Using Git Command Line

```bash
# Navigate to your project directory
cd "Earnings Calculator"

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Add earnings calculator"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 4. Access Your Live Site

1. GitHub will build and deploy your site (this may take a few minutes)
2. Once deployed, your site will be available at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`
3. You can find the exact URL in the Pages settings

## Custom Domain (Optional)

If you want to use a custom domain:

1. In your repository settings, go to Pages
2. Enter your custom domain in the "Custom domain" field
3. Add a `CNAME` file to your repository root with your domain name
4. Configure your domain's DNS settings to point to GitHub Pages

## Updating Your Site

To update your site:

1. Make changes to your files locally
2. Commit and push changes to GitHub:
   ```bash
   git add .
   git commit -m "Update calculator"
   git push
   ```
3. GitHub Pages will automatically rebuild and deploy your changes

## Troubleshooting

### Site Not Loading
- Check that your repository is public
- Ensure you selected the correct branch and folder in Pages settings
- Wait a few minutes for the initial deployment

### Changes Not Appearing
- GitHub Pages can take a few minutes to update
- Check the Actions tab in your repository for deployment status
- Clear your browser cache

### 404 Error
- Make sure your main file is named `index.html`
- Verify the file is in the root directory of your repository

## Support

If you encounter any issues:
1. Check GitHub's [Pages documentation](https://docs.github.com/en/pages)
2. Review the repository's Actions tab for build errors
3. Ensure all file names and paths are correct

---

Your earnings calculator is now live and ready to use! 🚀