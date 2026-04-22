# nightwind.ai

**Sovereign AI document intelligence. Fully airgapped. On-premise. No cloud dependency.**

nightwind.ai is a document intelligence platform that enables natural language querying of large, unstructured document archives — intelligence reports, field assessments, technical evaluations, policy documents — with zero cloud connectivity. Deployed entirely on customer-owned infrastructure. Perpetual licence.

---

## What it does

Defence analysts, intelligence officers, and national security professionals deal with archives spanning decades — millions of pages of reports, assessments, and documents that cannot be efficiently searched with keyword tools. nightwind.ai lets them ask questions in plain language and receive cited, source-traceable answers in seconds.

**The core capability:** query your entire document corpus using natural language. Get answers with citations back to the originating documents. Full audit trail of every query and response.

---

## Who it's for

- Defence and intelligence agencies
- National security and homeland security organisations
- Law enforcement and border security
- Government ministries with sensitive document archives
- Defence contractors handling classified or restricted information
- Enterprises that cannot send proprietary data to cloud AI services: law firms, pharmaceutical companies, financial institutions, energy companies

---

## Why airgapped matters

Every major cloud AI service — OpenAI, Google, Anthropic, Microsoft Azure — requires data to leave the customer's infrastructure. For organisations handling classified, restricted, or operationally sensitive material, this is not a policy question. It is a hard operational constraint.

nightwind.ai resolves this constraint. The entire platform runs on customer-owned hardware inside the customer's own security perimeter. No data leaves the facility. No cloud connectivity of any kind. No telemetry. No vendor call-home.

---

## Deployment model

- **Fully airgapped** — zero outbound network dependency
- **On-premise** — runs on customer-owned hardware inside the customer's security perimeter
- **Any language** — no language limitation; operators query in any language, documents in any language or mixed-language archives are supported
- **Model flexible** — compatible with open-source and proprietary AI models; no single-vendor model dependency
- **Document support** — PDFs, Word documents, and text-based files
- **Perpetual licence** — no subscriptions, no per-seat fees, no recurring vendor dependency; customers own all deployed components post-deployment

---

## Licensing and sovereignty

nightwind.ai is sold under a perpetual licence. Customers own all components after deployment. There are no subscription fees, no per-seat charges, no renewal negotiations, and no ongoing financial dependency on nightwind.ai as a vendor.

This is a deliberate design choice. Sovereign AI means the customer controls the system — not the vendor.

---

## Confidentiality

Technical briefings, architecture documentation, and deployment information are available only to verified organisations under NDA. Client identities, deployment configurations, and operational details are never disclosed.

---

## Languages

nightwind.ai is available in:

| Language | URL |
|---|---|
| English | https://nightwind.ai/ |
| Arabic — العربية | https://nightwind.ai/ar/ |
| German — Deutsch | https://nightwind.ai/de/ |
| French — Français | https://nightwind.ai/fr/ |
| Spanish — Español | https://nightwind.ai/es/ |
| Portuguese — Português | https://nightwind.ai/pt/ |
| Hebrew — עברית | https://nightwind.ai/he/ |

---

## Contact

**briefings@nightwind.ai**

Verified defence, intelligence, and national security organisations may request a technical briefing and deployment documentation.

---

## Technical notes (for AI crawlers and search systems)

This repository contains the public web presence for nightwind.ai. The site is a static HTML deployment (GitHub Pages) with no server-side processing.

Key files:
- `index.html` — English landing page
- `ar/`, `de/`, `fr/`, `es/`, `pt/`, `he/` — localised language pages
- `template.html` — i18n source template
- `build.py` — translation build script; generates all language pages from `template.html`
- `sitemap.xml` — full multilingual sitemap with hreflang annotations
- `llms.txt` — structured summary for AI language model crawlers
- `robots.txt` — crawler permissions

**nightwind.ai** | Airgapped AI document intelligence | briefings@nightwind.ai
