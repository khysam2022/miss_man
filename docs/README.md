# Unity Miss Man - Support Website

This is a GitHub Pages website for Unity Miss Man support and privacy policy.

## Setup Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it something like `unity-miss-man-support` or `unity-miss-man-website`
3. Make it public (required for free GitHub Pages)

### 2. Upload Files to GitHub

You can upload the files in the `docs` folder using one of these methods:

**Option A: Using GitHub Web Interface**
1. Go to your repository on GitHub
2. Click "Add file" → "Upload files"
3. Drag and drop all files from the `docs` folder
4. Commit the changes

**Option B: Using Git Command Line**
```bash
cd /Users/samakaykhakatwilight/Documents/SWIFT/Unity/man/docs
git init
git add .
git commit -m "Initial commit: Support website and privacy policy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/docs" folder
6. Click "Save"

### 4. Access Your Website

After a few minutes, your website will be available at:
- `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

For example: `https://johndoe.github.io/unity-miss-man-support/`

## Customization

### Update Email Addresses

Before deploying, update the email addresses in:
- `index.html` - Replace `support@example.com` with your actual support email
- `privacy-policy.html` - Replace `privacy@example.com` with your actual privacy email

### Update App Information

Update the app information in `index.html`:
- App version
- Contact information
- FAQ content

### Customize Privacy Policy

Review and customize the privacy policy in `privacy-policy.html` to match your app's actual data collection and usage practices.

## File Structure

```
docs/
├── index.html          # Support page (main page)
├── privacy-policy.html # Privacy policy page
├── styles.css          # Stylesheet for all pages
└── README.md          # This file
```

## Privacy Policy URL

Once deployed, your privacy policy will be available at:
- `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/privacy-policy.html`

You can use this URL in your iOS app's App Store listing and in your app's settings.

## Support

For questions about setting up GitHub Pages, visit: https://docs.github.com/en/pages

