# PocketForge Studio website

This repository contains the static website for pocketforgestudio.co.uk.

**Publication status:** Website content is prepared for GitHub Pages. Individual app Terms of Service are *drafts* and are not final or appropriate for submitting to Google Play Console until reviewed.

## Project contents

- `index.html`: developer homepage and app portfolio
- `assets/style.css`: responsive dark design
- `terms/index.html`: index of app-specific legal drafts
- `terms/*/index.html`: four draft app-specific Terms of Service pages

## Publishing and domain

1. Review legal drafts and replace notices after confirming that each page is accurate for the actual released app. In particular, review subscriptions, refunds, account deletion, privacy policies, statutory rights and trader contact details.
2. On GitHub Free, make this repository public before enabling Pages. Published content will be publicly readable.
3. In Settings → Pages, use **Deploy from a branch**, `main`, `/(root)`.
4. In Settings → Pages, add custom domain `pocketforgestudio.co.uk`.
5. In Fasthosts DNS, add the GitHub Pages apex A records using the current official GitHub documentation. Don't change MX/email TXT records.
6. When GitHub validates the site and certificate, enable **Enforce HTTPS** and check all links.
7. Verify the website/domain in Google Search Console and add it to Google Play Console → Account details → About you → Website.
8. Add an app's terms link to its Google Play trader declaration only once that app's final terms page is live.

This repo deliberately contains no credentials, analytics scripts, user tracking, app binaries, Firebase configuration, or changes to other projects.

Contact: pocketforgeapps@gmail.com
