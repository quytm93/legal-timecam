# TimeCam Legal Pages

Legal pages for TimeCam iOS app, hosted on GitHub Pages.

## Pages

- **[index.html](index.html)** - Marketing/Landing page
- **[privacy.html](privacy.html)** - Privacy Policy
- **[terms.html](terms.html)** - Terms of Service
- **[support.html](support.html)** - Support page

## URLs (after deployment)

| Page | URL |
|------|-----|
| Marketing | https://quytm93.github.io/legal-timecam/ |
| Privacy Policy | https://quytm93.github.io/legal-timecam/privacy.html |
| Terms of Service | https://quytm93.github.io/legal-timecam/terms.html |
| Support | https://quytm93.github.io/legal-timecam/support.html |

## App Store Connect URLs

Use these URLs when submitting to App Store:

- **Privacy Policy URL**: `https://quytm93.github.io/legal-timecam/privacy.html`
- **Terms of Service URL**: `https://quytm93.github.io/legal-timecam/terms.html`
- **Support URL**: `https://quytm93.github.io/legal-timecam/support.html`
- **Marketing URL**: `https://quytm93.github.io/legal-timecam/`

## Deployment

1. Push to GitHub:
```bash
git init
git add .
git commit -m "Add legal pages for TimeCam"
git branch -M main
git remote add origin https://github.com/quytm93/legal-timecam.git
git push -u origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: main, folder: / (root)
   - Save

3. Wait a few minutes for deployment

## Customization

Update the following in all files:
- Contact email: Currently set to `support@timecam.app` and `privacy@timecam.app`
- App Store download link: Replace `#` in index.html with actual App Store URL
- Company name/info if needed

## License

Copyright 2026 TimeCam. All rights reserved.
