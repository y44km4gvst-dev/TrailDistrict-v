# TrailDistrict Public-Facing MVP

This is the public customer-facing prototype for the Vancouver pilot.

Pages:
- index.html — home
- trails.html — all five trails
- trail.html?id=... — individual trail experience
- go.html?business=...&trail=... — referral/check-in destination prototype
- about.html — how TrailDistrict works
- 404.html — fallback

## Deploy
This is a static HTML site. It can be deployed to GitHub Pages or Cloudflare Pages.

## Important
The initial businesses are marked prospective. Do not represent them as partners, sponsors, affiliates, or participating stops until each business explicitly approves participation. Do not publish an offer until its exact terms are approved.

The public prototype records demo referral/check-in events only in the visitor's browser localStorage. It is NOT centralized analytics. Production tracking needs a server/database/API.

The site uses Google Maps search links for directions. Replace/add official business website/social links only after verifying current information and receiving appropriate permission.

## Suggested production structure
Public: home, trails, business profiles, referral/check-in routes.
Private: CRM, onboarding, analytics, business reporting.
