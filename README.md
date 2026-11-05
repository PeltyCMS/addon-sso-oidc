# OpenID Connect

Sign in to PeltyCMS with OpenID Connect

Official **single sign-on** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `sso-oidc`.

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **OpenID Connect**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **OpenID Connect** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-oidc) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your OpenID Connect credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use OpenID Connect automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid OpenID Connect API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to OpenID Connect

## Get it

[OpenID Connect on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-oidc)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/sso-oidc
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
