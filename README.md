# Mobile Call Rejecter Site

Static website for the Mobile Call Rejecter app.

## Files

- `index.html`: main public landing page / official developer website
- `styles.css`: site styles
- `robots.txt`: crawler-friendly rules for app-ads.txt verification
- `app-ads.txt.template`: rename to `app-ads.txt` after replacing the publisher ID

## Important for AdMob / app-ads.txt

1. Add your final website URL to the Play Store app listing as the Developer Website.
2. Publish `app-ads.txt` at the root of the same domain.
3. Ensure the final URL works as:
   - `https://your-domain.com/app-ads.txt`
   - preferably also reachable through HTTP or properly redirected
4. Ensure the file returns HTTP 200.

## Suggested deployment structure

/
- index.html
- styles.css
- robots.txt
- app-ads.txt

## Current external links used in the site

- Play Store: `https://play.google.com/store/apps/details?id=com.mobilecallrejecter.app&hl=en`
- Privacy policy: `https://mobile-call-rejecter-privacy.pages.dev/`
- Donation page: `https://donate-page-kiz.pages.dev/donate/`

Update these if your production URLs change.
