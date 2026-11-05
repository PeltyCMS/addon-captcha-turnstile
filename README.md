# Cloudflare Turnstile

Stop bots on PeltyCMS forms with Cloudflare Turnstile

Official **captcha / bot protection** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `captcha-turnstile`.

## Why this addon

Anyone tired of spam accounts and bot ticket floods.

## Features

- Protect login, register, tickets and checkout with **Cloudflare Turnstile**
- Server-side verification inside the WASM captcha addon
- Site keys configured once in Pelty settings
- No theme PHP hacks

## How it works

1. Install **Cloudflare Turnstile** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-turnstile) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Cloudflare Turnstile credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Cloudflare Turnstile automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Cloudflare Turnstile API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Cloudflare Turnstile

## Get it

[Cloudflare Turnstile on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-turnstile)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/captcha-turnstile
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
