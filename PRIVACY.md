# Privacy Policy — UniverSoulSun Connectors

**Last updated:** October 11, 2026
**Contact:** hello.universoulsun@gmail.com

## What this is

UniverSoulSun Connectors is a set of open-source publishing tools — one per
platform (TikTok, YouTube, Pinterest, LinkedIn) — that let the owner publish
content to their **own** social media accounts through each platform's official
API, operated via their AI assistant. It is a **single-user** tool: it only
ever accesses the account of the person who connected it.

## Data we access

Only what the official API scopes grant, and only on your own account:

- **Pinterest:** your boards, pins, and basic account information
  (`pins:read`, `pins:write`, `boards:read`, `boards:write`,
  `user_accounts:read`). The connector creates image/video pins on boards you
  select, with titles, descriptions, and link URLs you approve.
- **TikTok / YouTube / LinkedIn:** the same pattern — only the scopes each
  platform requires to upload or publish the content you choose, on your own
  account.

## How your data is used

- Solely to perform the publishing actions **you** request — for example,
  creating a pin from media you provided.
- Nothing is published without your explicit approval per item
  (drafts-first workflow: content is prepared, you review, then it goes out).
- Media you choose to publish is transmitted to the platform through its
  official API in order to create the post. We do not retain a copy afterward.

## What we don't do

- No selling, renting, or sharing of your data with third parties.
- No analytics, tracking, or advertising profiles.
- No autonomous posting — the tools cannot publish without your approval.
- No access to anyone else's account or data.

## Credentials and security

- OAuth tokens are stored in an encrypted credential vault and supplied to API
  calls at runtime. They are never written to code, logs, or chat transcripts.
- API request logging redacts authorization headers.
- You can revoke access at any time from the platform's authorized-apps
  settings (this immediately invalidates the tokens), or by contacting us.

## Data retention

Tokens persist until you revoke them. Published content lives on the platform
under that platform's own policies. We keep no copy of your media or account
data.

## Children

This tool is not directed at children under 13, and we do not knowingly
collect data from children.

## Changes to this policy

If this policy changes, the updated version will be posted at this URL with a
new "Last updated" date.

## Contact

Questions about this policy: **hello.universoulsun@gmail.com**
