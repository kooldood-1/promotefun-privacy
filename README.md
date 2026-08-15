# promote.fun Discord bot privacy policy

The public privacy policy for the promote.fun Discord bot. This repository is the
source of truth for that document. If the policy changes, change it here.

`index.html` is a single self-contained page. No build step, no dependencies, no
external assets, no fonts, no trackers. It works from any static host.

## Where it is live

| Host | URL |
| --- | --- |
| GitHub Pages | https://kooldood-1.github.io/promotefun-privacy/ |
| Vercel | set after import, see below |

## Deploying to Vercel

1. Go to https://vercel.com/new and import this repository.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. The page is live at `https://<project>.vercel.app`.

`vercel.json` also serves the same page at `/privacy` and `/discord-privacy`, so a
custom domain can use a tidy path such as `https://promote.fun/discord-privacy`.

## Keeping it in sync with the bot

The bot repository holds `PRIVACY.md`, the Markdown version of the same document.
If you edit one, edit the other. The URL the bot shows to members is the
`privacyPolicyUrl` key in the bot's `config.json`.

## Before this counts as published

- [ ] `privacy@promote.fun` accepts mail, or the address in section 8 is changed
      to one that does
- [ ] The retention periods in section 5 match what the bot actually does
- [ ] The third parties in section 4 are still the ones receiving data
