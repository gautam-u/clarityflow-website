# ClarityFlow Website

Marketing website and legal pages for ClarityFlow iOS app.

## Structure

- `index.md` - Main landing page
- `terms.md` - Terms of Service
- `privacy-policy.md` - Privacy Policy
- `_config.yml` - Jekyll configuration
- `_layouts/` - Page layouts (will use GitHub Pages default theme)
- `assets/` - Images and resources

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select branch: `main` (or `master`)
4. Select folder: `/ (root)`
5. Save

The site will be available at: `https://gautam-u.github.io/clarityflow-website/`

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000/clarityflow-website/
```

## URLs for App

After deploying to GitHub Pages, use these URLs in your app:

- **Terms of Service:** `https://gautam-u.github.io/clarityflow-website/terms/`
- **Privacy Policy:** `https://gautam-u.github.io/clarityflow-website/privacy-policy/`

## Customization

Edit `_config.yml` to update:
- App name and description
- Contact email
- App Store link (when available)
- Features list

## License

© 2025 ClarityFlow. All rights reserved.
