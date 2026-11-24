# TIKFINDER

Responsive static website for exploring publicly available TikTok profile information.

## Hosting
The project is connected to Cloudflare Pages as `tikfinder.pages.dev`. The production branch is `main`; pushes to `main` are intended to publish the static site automatically.

## Website features
- Responsive dark interface for desktop and mobile.
- Home, Profile, Stories, Videos, Followers, Following, LIVE, Analytics and Saved sections.
- Username or public profile URL search interface.
- English, French and Arabic language selector.
- Privacy-first messaging: public information only; no private account access or password collection.

## Data status
The current website is a front-end. Live TikTok profile lookup, active public Stories, followers/following and analytics are not connected yet. These require a reliable, permitted data provider or authorized API. The site does not invent results. Never put API credentials in `index.html`; use server-side secrets.
