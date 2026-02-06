# GitHub Pages Setup Guide

## Quick Fix for 404 Error

Your privacy policy HTML files are ready but need to be on the `main` branch for GitHub Pages to serve them.

## Step-by-Step Instructions

### 1. Merge the Pull Request

First, you need to merge the pull request containing the privacy policy files to the `main` branch:

1. Go to your repository: https://github.com/philsellars/privacy-pregnancytrackerapp
2. Click on the **Pull requests** tab
3. Find the PR titled "Add privacy policy HTML pages for App Store compliance"
4. Review the changes (privacy-policy.html, index.html, README.md, .nojekyll)
5. Click **Merge pull request**
6. Click **Confirm merge**

### 2. Enable GitHub Pages

After merging, enable GitHub Pages:

1. Stay on your repository page
2. Click **Settings** (in the repository menu, not your account settings)
3. In the left sidebar, scroll down and click **Pages**
4. Under "Build and deployment" section:
   - **Source**: Deploy from a branch
   - **Branch**: Select `main` from the dropdown
   - **Folder**: Select `/ (root)` from the dropdown
5. Click **Save**

### 3. Wait for Deployment

GitHub will now build and deploy your site:

- You'll see a blue box that says "GitHub Pages source saved"
- After 1-2 minutes, the box will turn green with a checkmark
- The message will show: "Your site is live at https://philsellars.github.io/privacy-pregnancytrackerapp/"

### 4. Verify It Works

Once deployed, test the URLs:

- Main URL: https://philsellars.github.io/privacy-pregnancytrackerapp/
- Direct link: https://philsellars.github.io/privacy-pregnancytrackerapp/privacy-policy.html

Both should show your privacy policy page (index.html redirects to privacy-policy.html).

## Common Issues and Solutions

### Still seeing 404?

**Check 1: Is the PR merged?**
- Go to your repository
- Look at the branch dropdown (usually shows "main")
- Verify it says "main" and you can see index.html and privacy-policy.html in the file list

**Check 2: Is GitHub Pages enabled?**
- Go to Settings → Pages
- Verify "Source" shows: main / (root)
- Look for the green success message with your site URL

**Check 3: Wait a bit longer**
- GitHub Pages deployment can take up to 10 minutes in rare cases
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Try opening in an incognito/private window

**Check 4: Check GitHub Pages status**
- In Settings → Pages, there's a "Visit site" button
- If you see any error messages in the GitHub Pages section, they'll guide you to the issue

### Need to update the privacy policy later?

1. Edit the files on the `main` branch (via GitHub web interface or git)
2. Commit the changes
3. GitHub Pages will automatically rebuild and redeploy (takes 1-2 minutes)

## What We Created

- **privacy-policy.html** - Your Apple-compliant privacy policy
- **index.html** - Landing page that redirects to the privacy policy
- **.nojekyll** - Tells GitHub Pages not to use Jekyll (ensures files are served as-is)
- **README.md** - Documentation for the repository

## For Apple App Store Submission

Once GitHub Pages is live, use this URL in your App Store Connect submission:

```
https://philsellars.github.io/privacy-pregnancytrackerapp/
```

This is your official privacy policy URL that Apple requires.
