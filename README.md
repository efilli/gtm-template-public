# Efilli CMP — Google Tag Manager Community Template (Source)

This repository contains the source files for the Efilli Consent Management Platform (CMP) Google Tag Manager (GTM) Community Template. It is intended for maintainers, reviewers, and developers—not for end users.

End users should install this template directly from the GTM Community Template Gallery by searching for “Efilli CMP”.

## What this template does

Efilli CMP’s GTM template integrates with Google Consent Mode, allowing consent states collected by Efilli to be reflected inside GTM and Google products.

Highlights:

- Google Consent Mode v2 support (ad_user_data, ad_personalization, ad_storage, analytics_storage, functionality_storage, personalization_storage, security_storage)
- Optional Efilli SDK loader with automatic or manual bundle URL resolution
- Region-based default consent initialization and wait_for_update support
- Optional URL Passthrough and Ads Data Redaction flags via gtagSet

## Installation (for end users)

This repository is not meant to be imported manually by end users. Instead, install from the Community Template Gallery:

1. In GTM, open your container (Web).
2. Go to Templates > Search gallery.
3. Search for “Efilli CMP” and add the template.
4. Create a new Tag using the “Efilli CMP” tag type and configure options as needed.

## Support

- Issues: please open a GitHub issue in this repository with details and reproduction steps.
- Efilli website and docs: https://efilli.com
- Maintainer contact: halil@efilli.com

## License

Apache License 2.0 — see `LICENSE` for details.
