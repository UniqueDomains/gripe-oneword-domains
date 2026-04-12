# Available .GRIPE One-Word Domains (9,832)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C832%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C832%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .gripe one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,832 rows · **Live catalog:** 9,832 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/gripe`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/gripe?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./gripe.csv">CSV</a> / <a href="./gripe.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GRIPE search](https://unique.domains/domains/tld/gripe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GRIPE search](https://unique.domains/domains/tld/gripe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GRIPE one-word domain catalog.

### Files

- `gripe.csv` — public CSV extract (9,832 rows)
- `gripe.json` — public JSON extract (9,832 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/gripe-oneword-domains/main/gripe.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| alpha.gripe    | available | $8.98     | —             | 90             | 54     | 5      | namecheap        |
| first.gripe    | resell    | $8.98     | —             | 80             | 41     | 5      | GoDaddy.com, LLC |
| cloud.gripe    | premium   | $85.80    | $85.80        | 70             | 59     | 5      | namecheap        |
| free.gripe     | available | $8.98     | —             | 88             | 54     | 4      | namecheap        |
| book.gripe     | resell    | —         | —             | 82             | 55     | 4      | NameCheap, Inc.  |
| ace.gripe      | premium   | $41.25    | $41.25        | 88             | 57     | 3      | name.com         |
| fast.gripe     | available | $8.98     | —             | 82             | 53     | 4      | namecheap        |
| buy.gripe      | resell    | —         | —             | 106            | 53     | 3      | Spaceship, Inc.  |
| data.gripe     | premium   | $42.90    | $42.90        | 70             | 56     | 4      | namecheap        |
| true.gripe     | available | $8.98     | —             | 86             | 52     | 4      | namecheap        |
| that.gripe     | resell    | —         | —             | 94             | 36     | 4      | GoDaddy.com, LLC |
| business.gripe | premium   | $85.80    | $85.80        | 100            | 53     | 8      | namecheap        |
| world.gripe    | available | $8.98     | —             | 90             | 51     | 5      | namecheap        |
| sexy.gripe     | resell    | —         | —             | 82             | 34     | 4      | GoDaddy.com, LLC |
| one.gripe      | premium   | $250      | $250          | 132            | 50     | 3      | name.com         |
| simple.gripe   | available | $8.98     | —             | 128            | 48     | 6      | namecheap        |
| game.gripe     | premium   | $41.25    | $41.25        | 120            | 50     | 4      | name.com         |
| epic.gripe     | available | $8.98     | —             | 88             | 47     | 4      | namecheap        |
| design.gripe   | premium   | $82.50    | $82.50        | 108            | 50     | 6      | name.com         |
| only.gripe     | available | $8.98     | —             | 110            | 46     | 4      | namecheap        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,832-row public sample | 9,832 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/gripe?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/gripe?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=related_pricing)

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
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GRIPE One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GRIPE page](https://unique.domains/domains/tld/gripe?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
