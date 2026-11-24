# TIKFINDER

Responsive front-end for a TikTok public-profile exploration website.

## Deployment
This repository includes a GitHub Pages workflow at `.github/workflows/pages.yml`.
In GitHub, open **Settings → Pages** and set **Build and deployment → Source: GitHub Actions** if it is not already selected. GitHub may require the repository to be public on plans that do not support Pages for private repositories.

## Current implementation status
- Responsive dark interface for desktop and mobile.
- Navigation sections: Home, Profile, Stories, Videos, Followers, Following, LIVE, Analytics and Saved.
- Search form interaction and language selector (English, French, Arabic).
- Clear disclosure that live data is not connected yet.

## Live TikTok data
Real profile lookup, Story playback, followers/following and analytics require a permitted, reliable data provider or authorized API. The front-end does not fake results. Add any API credentials only to server-side secrets (never to `index.html`). Respect provider terms, platform rules and account privacy. Private or expired Stories cannot be guaranteed or accessed.

## Publish
After enabling GitHub Actions as the Pages source, push to `main`. The workflow deploys the root static site. Open the Pages URL shown in repository Settings → Pages.
