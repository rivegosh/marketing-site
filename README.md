# Rive Gosh — marketing site

Static landing pages for `rivegosh.com`. Hosted on GitHub Pages.

## Routes

- `/` — audience choice page (Clients / Affiliates)
- `/clients` — VIP chauffeur LP for European travelers in the USA
- `/affiliates` — B2B partner LP for travel agencies / hotels / conciergeries

## Stack

- Pure HTML/CSS, no build step.
- Bilingual FR/EN with FR default + EN toggle.
- Brand foundation: Playfair Display + Inter, champagne `#CCC593` on dark luxury `#0f0c08`.
- Deploys via GitHub Actions on every push to `main`.

## Source of truth

- Audience taxonomy: [rivegosh/concierge-rivegosh#131](https://github.com/rivegosh/concierge-rivegosh/issues/131)
- Brand foundation: [rivegosh/concierge-rivegosh#132](https://github.com/rivegosh/concierge-rivegosh/issues/132)
- Marketing blueprint: [rivegosh/concierge-rivegosh#133](https://github.com/rivegosh/concierge-rivegosh/issues/133)

## DNS (rivegosh.com)

- **A records:** GitHub Pages IPs `185.199.108.153`, `109.153`, `110.153`, `111.153`
- **CNAME `www`:** `rivegosh.github.io`
- **MX records preserved:** Google Workspace (Daniel's `@rivegosh.com` email)
