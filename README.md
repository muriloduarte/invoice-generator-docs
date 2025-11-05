# 📄 Invoice Generator - Privacy Policy & Documentation

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://muriloduarte.github.io/invoice-generator-docs/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This repository contains the privacy policy and terms of use documentation for the **Invoice Generator** Chrome extension.

## 🌐 Live Site

The documentation is hosted via GitHub Pages and accessible at:

**https://muriloduarte.github.io/invoice-generator-docs/**

## 📋 What's Included

- **Privacy Policy** (Portuguese & English)
- **Terms of Use** (Portuguese)
- Responsive design optimized for all devices
- Professional styling with modern UI

## 🗂️ Repository Structure

```
invoice-generator-docs/
├── index.html           # Privacy Policy (Portuguese)
├── privacy-en.html      # Privacy Policy (English)
├── terms.html          # Terms of Use (Portuguese)
├── README.md           # This file
└── assets/
    └── style.css       # Styling and responsive design
```

## 🚀 How to Deploy

### 1. Enable GitHub Pages

1. Go to **Settings** → **Pages** in this repository
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**
4. Wait ~2-10 minutes for the site to be published

### 2. Update Your Chrome Extension

Add the following to your `manifest.json`:

```json
{
  "homepage_url": "https://muriloduarte.github.io/invoice-generator-docs/"
}
```

### 3. Update Chrome Web Store Listing

1. Go to your extension's page in the [Chrome Web Store Developer Dashboard](https://chrome.google.com/webstore/devconsole)
2. Navigate to the **Privacy** section
3. Add the Privacy Policy URL:
   ```
   https://muriloduarte.github.io/invoice-generator-docs/
   ```
4. Save and publish the changes

## 📝 Updating the Privacy Policy

To update the privacy policy:

1. Edit the relevant HTML file (`index.html` for Portuguese, `privacy-en.html` for English)
2. Update the "Last updated" date
3. Commit and push the changes
4. GitHub Pages will automatically update the live site

```bash
git add .
git commit -m "Update privacy policy"
git push origin main
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `assets/style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... other colors ... */
}
```

### Adding More Languages

1. Create a new file: `privacy-{lang-code}.html`
2. Copy the structure from `privacy-en.html`
3. Translate the content
4. Update the language selector links in all files

## ✅ Compliance

This privacy policy template is designed to comply with:

- ✅ **LGPD** (Lei Geral de Proteção de Dados) - Brazil
- ✅ **GDPR** (General Data Protection Regulation) - EU
- ✅ **Chrome Web Store Developer Program Policies**

## 📧 Contact

For questions about this documentation:

- **Email**: privacy@invoicegenerator.com
- **GitHub Issues**: [Create an issue](https://github.com/muriloduarte/invoice-generator-docs/issues)

## 📄 License

This documentation is provided under the [MIT License](LICENSE).

---

**Note**: Make sure to customize the email addresses and specific details according to your actual extension before going live.
