# 🔄 Social previews: refresh guide + share-image ledger

When a link to one of Psanctuary's GitHub Pages sites is pasted into a chat app, the app shows a
preview card (title, description and a share image) that it fetched **once** and then **cached**.
After a share image or title changes, old previews keep showing until each app is told to look again.
This file lists how to do that for each app, and which pages have their own tailored share image.

*Generated 2026-10-23 by the arrival kit's `social/social-previews.mjs` (canonical copy in
[my-template](https://github.com/drasticstatic/my-template/tree/main/changelog-template/arrival/social)).
Re-run it after deploys that add pages or change share images.*

## 🧰 How to refresh each app

| App | How to make it re-fetch | Notes |
|---|---|---|
| ✈️ **Telegram** | Message [@WebpageBot](https://t.me/WebpageBot) the link (you can send several links, one per line) | The bot replies with the fresh preview; new shares use it right away |
| 💼 **LinkedIn** | Paste the link into [Post Inspector](https://www.linkedin.com/post-inspector/) | Inspecting re-scrapes the page |
| 📘 **Facebook / Messenger** | Paste into the [Sharing Debugger](https://developers.facebook.com/tools/debug/) and press **Scrape Again** | Also accepts a batch of links |
| 💬 **Discord** | No refresh tool. Share the link with a harmless suffix such as `?v=2` | Discord caches per exact URL, so a new suffix gets a new preview |
| 🟪 **Slack** | No refresh tool. Use the `?v=2` suffix trick | Old messages keep their old unfurl |
| 🐦 **X (Twitter)** | No public validator any more. Use the `?v=2` suffix, or wait (cards refresh on their own, roughly a week) | |
| 🟢 **WhatsApp** | No refresh tool. Use the `?v=2` suffix | WhatsApp caches aggressively |
| 🦋 **Bluesky** / 🐘 **Mastodon** | Fetched when a post is written; nothing to clear | Each Mastodon server fetches its own copy |
| 💬 **iMessage** | Fetched on the sender's phone at send time | Nothing to clear |

**Rule of thumb:** after changing a share image, refresh Telegram (@WebpageBot), LinkedIn and
Facebook for the pages listed below. Use the `?v=2` suffix anywhere else.

## 🖼️ Share-image ledger

17 pages checked: **14 tailored**, 3 using the default card,
0 with no share image.

### ✨ Pages with their own tailored share image

| Page | Title | Share image |
|---|---|---|
| [psanctuary.github.io/donate/](https://psanctuary.github.io/donate/) | Donate — Psanctuary on GitHub | [image](https://psanctuary.github.io/changelog-astro-public/og/page/donate.jpg) |
| [psanctuary.github.io/pledge/](https://psanctuary.github.io/pledge/) | A pledge of support — Psanctuary on GitHub | [image](https://psanctuary.github.io/changelog-astro-public/og/page/pledge.jpg) |
| [psanctuary.github.io/map/](https://psanctuary.github.io/map/) | Map — Psanctuary on GitHub | [image](https://psanctuary.github.io/changelog-astro-public/og/page/map.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog](https://psanctuary.github.io/changelog-astro-public/changelog) | Changelog — Psanctuary | [image](https://psanctuary.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [psanctuary.github.io/changelog-astro-public/library](https://psanctuary.github.io/changelog-astro-public/library) | Library — Psanctuary | [image](https://psanctuary.github.io/changelog-astro-public/og/page/library.jpg) |
| [psanctuary.github.io/changelog-astro-public/ledger](https://psanctuary.github.io/changelog-astro-public/ledger) | Ledger — Psanctuary AstroLog | [image](https://psanctuary.github.io/changelog-astro-public/og/ledger.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-22-a-decentralized-church-a-pledge-and-one-door](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-22-a-decentralized-church-a-pledge-and-one-door) | How a decentralized church can work, a pledge of support, and one door to the community — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-22-a-decentralized-church-a-pledge-and-one-door.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in) | A navbar on every page, a map with pictures, and one window for every way in — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive) | Choose how you arrive: a welcome, / to search, and faces on every change — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-12-choose-how-you-arrive.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card) | Share one entry, and it arrives with its own spore print — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-12-every-entry-shares-with-its-own-card.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new) | Reading mode, and what's new since your last visit — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-12-reading-mode-and-whats-new.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change) | The ledger: every public change, in plain words — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-12-the-ledger-every-public-change.jpg) |
| [psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid](https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid) | The foundation is laid: Psanctuary gets a home on GitHub — Psanctuary Changelog | [image](https://psanctuary.github.io/changelog-astro-public/og/changelog/github/2026-10-11-the-foundation-is-laid.jpg) |
| [psanctuary.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe](https://psanctuary.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe) | How this changelog stays public-safe — Psanctuary Library | [image](https://psanctuary.github.io/changelog-astro-public/og/library/how-this-changelog-stays-public-safe.jpg) |

### 🪪 Pages using the default card

- [psanctuary.github.io/](https://psanctuary.github.io/)
- [psanctuary.github.io/changelog-astro-public/](https://psanctuary.github.io/changelog-astro-public/)
- [psanctuary.github.io/changelog-astro-public/changelog/github](https://psanctuary.github.io/changelog-astro-public/changelog/github)

## 📋 Copy-paste list for @WebpageBot

```
https://psanctuary.github.io/
https://psanctuary.github.io/donate/
https://psanctuary.github.io/pledge/
https://psanctuary.github.io/map/
https://psanctuary.github.io/changelog-astro-public/
https://psanctuary.github.io/changelog-astro-public/changelog
https://psanctuary.github.io/changelog-astro-public/library
https://psanctuary.github.io/changelog-astro-public/ledger
https://psanctuary.github.io/changelog-astro-public/changelog/github
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-22-a-decentralized-church-a-pledge-and-one-door
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change
https://psanctuary.github.io/changelog-astro-public/changelog/github/2026-10-11-the-foundation-is-laid
https://psanctuary.github.io/changelog-astro-public/library/how-this-changelog-stays-public-safe
```
