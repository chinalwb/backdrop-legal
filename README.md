# backdrop-legal — moved

This project moved to **[chinalwb/backdrop-me](https://github.com/chinalwb/backdrop-me)**,
served at **https://chinalwb.github.io/backdrop-me/**. All site work happens there.

The repo was renamed from `backdrop-legal` to `backdrop-me` in June 2026. GitHub Pages URLs
don't follow a rename, so this stub was created to keep the old addresses working.

## What's here

Two redirect pages, served by GitHub Pages from `main`:

| Old URL | Redirects to |
|---|---|
| https://chinalwb.github.io/backdrop-legal/ | https://chinalwb.github.io/backdrop-me/ |
| https://chinalwb.github.io/backdrop-legal/privacy-policy.html | https://chinalwb.github.io/backdrop-me/privacy-policy.html |

## Keep it public, with Pages on

Some places still link to the old privacy-policy URL:

- **Galaxy Store listing:** the Seller Portal privacy-policy field
  (`DetailMain.sellerPrivatePolicy` in
  https://galaxystore.samsung.com/api/detail/com.chinalwb.backdrop).
- **App v1.1.0:** the in-app "Privacy policy" link.

If this repo goes private or Pages is turned off, those links 404, and a dead privacy-policy
link can get the app flagged in store review. This happened once (found 2026-10-17, fixed
2026-10-25).

## When it can be deleted

Delete this repo only after both:

1. The live Galaxy Store listing's privacy-policy URL points to `backdrop-me`.
2. No app version with the old in-app link (v1.1.0) is still on sale.
