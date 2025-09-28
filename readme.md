# Mobile Pro League - GitHub Pages Site


This repository contains a minimal, GitHub Pages-ready website for **Mobile Pro League** (English). It includes required pages for the TikTok Developer Portal approval: **Terms of Service** and **Privacy Policy**, plus a Contact page, sitemap and verification file example.


## Files
- `index.html` - Home page (links to Terms & Privacy)
- `terms-en.html` - Terms of Service (English)
- `privacy-en.html` - Privacy Policy (English)
- `contact.html` - Contact / Socials
- `.well-known/tiktok-verification.txt` - placeholder file for TikTok URL-prefix verification
- `robots.txt` - basic robots rules
- `sitemap.xml` - sitemap for search engines
- `README.md` - this file


## How to use
1. Create public repo on GitHub and push these files to the `main` branch.
2. Enable GitHub Pages: Settings → Pages → Branch `main` / folder `/root`.
3. Your site will be available at: `https://<your-username>.github.io/<repo-name>/`
4. Add the full URLs to the TikTok Developer Portal:
- Terms of Service URL: `https://<your-username>.github.io/<repo-name>/terms-en.html`
- Privacy Policy URL: `https://<your-username>.github.io/<repo-name>/privacy-en.html`
5. If TikTok requests URL-prefix verification, download the verification token from TikTok and paste it into `.well-known/tiktok-verification.txt` then commit.