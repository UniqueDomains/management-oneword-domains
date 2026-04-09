# Available .MANAGEMENT One-Word Domains (5,622,464)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C808%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C464%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .management one-word domains from Unique Domains.

> **Important:** this repository is a **public 8,808-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,464 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/management`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/management?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_open_search"><b>Open live .MANAGEMENT search</b></a> ·
  <a href="https://unique.domains/domains/tld/management?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_create_radar"><b>Create .MANAGEMENT Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/management?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./management.csv"><b>Download CSV</b></a> ·
  <a href="./management.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MANAGEMENT one-word domain catalog.

### Files

- `management.csv` — public CSV extract (8,808 rows)
- `management.json` — public JSON extract (8,808 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full .MANAGEMENT catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live .MANAGEMENT catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/management-oneword-domains/main/management.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar       |
| -------------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | --------------- |
| daniel.management    | available | $14.99         | —             | 76             | 52     | 6      | name.com        |
| silver.management    | resell    | $34.98         | —             | 56             | 37     | 6      | Dynadot Inc     |
| food.management      | premium   | $85.80         | $85.80        | 94             | 44     | 4      | namecheap       |
| snap.management      | available | $14.99         | $33.99        | 90             | 46     | 4      | name.com        |
| clean.management     | resell    | —              | —             | 130            | 99     | 5      | Dynadot Inc     |
| research.management  | premium   | $85.80         | $85.80        | 92             | 41     | 8      | namecheap       |
| nice.management      | available | $14.99         | $33.99        | 86             | 44     | 4      | name.com        |
| assistant.management | resell    | —              | —             | 74             | 98     | 9      | Dynadot Inc     |
| order.management     | premium   | $82.50         | $82.50        | 78             | 41     | 5      | name.com        |
| aaa.management       | available | $14.99         | —             | 70             | 42     | 3      | name.com        |
| prime.management     | resell    | —              | —             | 76             | 82     | 5      | Dynadot Inc     |
| dynamic.management   | premium   | $123.75        | $123.75       | 94             | 34     | 7      | name.com        |
| mark.management      | available | $14.99         | $33.99        | 66             | 42     | 4      | name.com        |
| wise.management      | resell    | —              | —             | 98             | 72     | 4      | Spaceship, Inc. |
| choice.management    | premium   | $14.99         | $33.99        | 74             | 32     | 6      | name.com        |
| quick.management     | available | $14.99         | $33.99        | 72             | 41     | 5      | name.com        |
| easy.management      | resell    | —              | —             | 128            | 68     | 4      | NameCheap, Inc. |
| show.management      | premium   | $128.70        | $128.70       | 72             | 31     | 4      | namecheap       |
| craft.management     | available | $14.99         | $33.99        | 70             | 41     | 5      | name.com        |
| identity.management  | resell    | —              | —             | 80             | 65     | 8      | Spaceship, Inc. |

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MANAGEMENT One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MANAGEMENT page](https://unique.domains/domains/tld/management?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_management_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
