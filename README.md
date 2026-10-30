# EduVerse Download Website

A lightweight, mobile-friendly APK download landing page for EduVerse, deployed as Cloudflare Workers static assets.

## Cloudflare Workers settings

- Build command: leave blank (there is no build step)
- Deploy command: `npx wrangler deploy`
- Preview command: `npx wrangler dev`

## GitHub Actions deployment

Add these repository secrets under **Settings → Secrets and variables → Actions**:

- `CLOUDFLARE_API_TOKEN`: Cloudflare API token with permission to edit Workers.
- `CLOUDFLARE_ACCOUNT_ID`: your Cloudflare account ID.

After adding the secrets, pushing to `main` automatically deploys the site.

## APK link

The download button is intentionally disabled until a real APK or GitHub Release URL is added. No APK binary is currently stored in this repository.
