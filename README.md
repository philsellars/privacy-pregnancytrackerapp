# Privacy Policy - Pregnancy Tracker App

This repository contains the privacy policy for the Pregnancy Tracker mobile application, hosted for Apple App Store compliance.

## Privacy Policy Pages

- **[privacy-policy.html](privacy-policy.html)** - Main privacy policy page
- **[index.html](index.html)** - Landing page with automatic redirect

## Data Collection

The Pregnancy Tracker app collects minimal information:
- Mother's Name (for personalization)
- Baby's Due Date (for milestone calculations)

## Data Storage

All data is stored **exclusively on the user's local device**. No data is transmitted to external servers or cloud services.

## GitHub Pages Setup Instructions

To make the privacy policy accessible via GitHub Pages:

### Step 1: Merge this PR to the main branch
The HTML files must be on the `main` branch for GitHub Pages to serve them. Merge the pull request that contains `index.html` and `privacy-policy.html`.

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** section in the left sidebar
4. Under "Source", select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

### Step 3: Wait for deployment
GitHub will automatically deploy your site. This usually takes 1-2 minutes. You'll see a message like:
> "Your site is published at https://philsellars.github.io/privacy-pregnancytrackerapp/"

### Step 4: Access your privacy policy
Once deployed, users can access the privacy policy at:
- `https://philsellars.github.io/privacy-pregnancytrackerapp/` (redirects to privacy policy)
- `https://philsellars.github.io/privacy-pregnancytrackerapp/privacy-policy.html` (direct link)

## Troubleshooting

**Getting a 404 error?**
- ✅ Ensure the PR has been merged to `main` branch
- ✅ Verify GitHub Pages is enabled in Settings → Pages
- ✅ Check that "Source" is set to `main` branch and `/ (root)` folder
- ✅ Wait 1-2 minutes for GitHub to deploy the site
- ✅ Clear your browser cache or try incognito mode
