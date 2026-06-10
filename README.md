# JAGPlaysGamesHelper website

Static approval-support website for the TikTok developer app `JAGPlaysGamesHelper`.

## Purpose

TikTok rejected the app with reviewer note: `Website must be fully developed.` This site provides the missing public-facing information:

- App purpose and workflow
- TikTok API scopes and usage
- Privacy Policy
- Terms of Use
- Support page
- Data deletion instructions
- OAuth callback information page
- Robots and sitemap files

## Suggested TikTok Developer Portal values

Website URL:

```text
https://x1xjagx1x.github.io/JAGPlaysGamesHelper/
```

Privacy Policy URL:

```text
https://x1xjagx1x.github.io/JAGPlaysGamesHelper/privacy.html
```

Terms of Service URL:

```text
https://x1xjagx1x.github.io/JAGPlaysGamesHelper/terms.html
```

OAuth redirect URI if TikTok requires a public HTTPS page:

```text
https://x1xjagx1x.github.io/JAGPlaysGamesHelper/oauth/callback.html
```

Preferred local OAuth redirect URI for local setup helpers, if TikTok accepts it:

```text
http://localhost:8765/callback
```

## Suggested app description

```text
JAGPlaysGamesHelper is a private creator operations tool used by JAG Plays Games to prepare, manage, and publish approved short-form gaming videos to connected social media accounts. The app uses TikTok Login and TikTok’s Content Posting API only after account authorization, and only for creator-approved uploads.
```

## Deployment notes

This directory is ready to publish as a GitHub Pages static site. Create a repository named `JAGPlaysGamesHelper`, copy these files into it, commit, push, and enable GitHub Pages from the repository settings.
