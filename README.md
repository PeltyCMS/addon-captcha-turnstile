# Cloudflare Turnstile

Stop bots on PeltyCMS forms with Cloudflare Turnstile

Official captcha / bot protection for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Anyone tired of spam accounts and bot ticket floods.

## Features

- Protect login, register, tickets and checkout with **Cloudflare Turnstile**
- Server-side verification inside the WASM captcha addon
- Site keys configured once in Pelty settings
- No theme PHP hacks

## How it works

1. Install **Cloudflare Turnstile** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-turnstile) inside Pelty Admin → Addons.
2. Open Pelty Admin → Settings, paste your Cloudflare Turnstile site + secret keys, and turn it on for login / register / tickets.
3. Customers hit checkout / login / order flow as usual — Cloudflare Turnstile runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Cloudflare Turnstile credentials
- Outbound HTTPS from your panel

## Get it

**[Cloudflare Turnstile on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-turnstile)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
