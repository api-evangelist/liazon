# Liazon

Liazon was a Buffalo, New York based operator of private benefits exchanges, best known for the Bright Choices Exchange, which helped small and mid-sized employers move to a defined-contribution benefits model and let their employees shop for health, dental, vision, life, and disability coverage through an online marketplace.

Backed by Bain Capital Ventures and Bessemer Venture Partners, the company was acquired by Towers Watson — now WTW — and no longer operates as an independent business.

## Status: acquired — no public API surface

As of a 2026-07-19 probe:

- `liazon.com` publishes **no A record** and serves no website over HTTP or HTTPS.
- MX records resolve to `willistowerswatson-com.mail.protection.outlook.com`.
- The domain is registered through MarkMonitor and remains active, indicating WTW retains it defensively rather than operating a product on it.
- No `api.`, `developer.`, `docs.`, or `brightchoices.` subdomain resolves.

There is no Liazon developer portal, documentation, API reference, SDK, or public API to catalog. Enrichment beyond domain-level DNS evidence is not applicable.

## Artifacts

- `security/liazon-domain-security.yml` — DNS/TLS probe evidence (SPF, DMARC `p=reject`, CAA GlobalSign, no DNSSEC, no HTTPS service).
