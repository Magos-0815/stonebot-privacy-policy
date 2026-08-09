# Stonebot public policy site

This repository contains the public Privacy Policy, Data Deletion Instructions,
and Terms of Use for Stonebot and its WhatsApp integration. It intentionally
contains no Stonebot source code, credentials, phone numbers, or message data.

## Meta App Dashboard values

Copy these exact public HTTPS URLs into the Meta App Dashboard:

| Meta field | URL |
| --- | --- |
| Privacy Policy URL | `https://magos-0815.github.io/stonebot-privacy-policy/` |
| User Data Deletion URL | `https://magos-0815.github.io/stonebot-privacy-policy/data-deletion/` |
| Terms of Service URL | `https://magos-0815.github.io/stonebot-privacy-policy/terms/` |

If Meta asks for an App Domain, use `magos-0815.github.io`.

## Claude Code handoff

1. Open **Meta App Dashboard → App settings → Basic**.
2. Enter the Privacy Policy URL above.
3. Enter the Terms of Service and User Data Deletion URLs if those fields are shown.
4. Save changes and open each URL in a signed-out browser to confirm it returns HTTPS `200`.
5. Report the completed fields and any remaining Meta validation message to the app owner.
6. The app owner should review the production settings and personally confirm **Publish / Go live**.

## Publishing

GitHub Pages publishes the root of the `main` branch. The site is plain static
HTML and CSS and does not require a build step.

## Updating the operator details

The current policy identifies the public project operator by GitHub account and
does not claim that Stonebot is operated by a registered company. If ownership
changes, update the operator and contact sections before publishing the change.
