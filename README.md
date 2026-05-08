# Available .GRIPE One-Word Domains (12,813)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C813%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .gripe one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,813 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,813 domains · **Median ask:** $10.79 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
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

- `gripe.csv` — public CSV extract (1,000 rows)
- `gripe.json` — public JSON extract (1,000 rows)
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

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| agents.gripe        | available | $8.98     | —             | 56             | 50     | 6      | namecheap         |
| online.gripe        | resell    | —         | —             | 70             | 62     | 7      | Sav.com, LLC - 18 |
| WiFi.gripe          | premium   | $46.20    | $46.20        | 83             | 37     | 5      | namecheap         |
| robots.gripe        | available | $6.99     | $6.99         | 62             | 47     | 6      | namesilo          |
| pages.gripe         | premium   | $82.50    | —             | 52             | 28     | 5      | name.com          |
| skills.gripe        | available | $8.98     | —             | 58             | 47     | 6      | namecheap         |
| Tests.gripe         | premium   | $92.40    | $92.40        | 49             | 21     | 5      | namecheap         |
| coins.gripe         | available | $8.98     | —             | 56             | 41     | 5      | namecheap         |
| gives.gripe         | premium   | $82.50    | —             | 52             | 12     | 5      | name.com          |
| matcha.gripe        | available | $8.98     | —             | 86             | 39     | 6      | namecheap         |
| VirginiaBeach.gripe | premium   | $92.40    | $92.40        | 58             | 9      | 14     | namecheap         |
| prompts.gripe       | available | $6.99     | $6.99         | 54             | 39     | 7      | namesilo          |
| tokens.gripe        | available | $6.99     | $6.99         | 51             | 36     | 6      | namesilo          |
| spectra.gripe       | available | $8.98     | —             | 62             | 34     | 7      | namecheap         |
| etc.gripe           | available | $8.98     | —             | 58             | 34     | 3      | namecheap         |
| Cats.gripe          | available | $8.98     | —             | 59             | 33     | 4      | namecheap         |
| teams.gripe         | available | $8.98     | —             | 62             | 32     | 5      | namecheap         |
| partners.gripe      | available | $8.98     | —             | 61             | 32     | 8      | namecheap         |
| letsgo.gripe        | available | $8.98     | —             | 57             | 31     | 7      | namecheap         |
| maps.gripe          | available | $8.98     | —             | 56             | 31     | 4      | namecheap         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,813 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is entirely made up of one-word .gripe domains. The words range from broad nouns like shelter, welfare, tree, and energy to more emotional or descriptive terms like feeling, bore, and adept. That makes this set uneven by design: some names read clearly as complaint, review, or advocacy brands, while others rely on irony or unusual positioning. When comparing these domains, start with whether the keyword works naturally with .gripe. Stronger choices feel intentional, memorable, and easy to explain out loud. Weaker choices may be cheap, but they can carry lower trust, narrower buyer appeal, or unclear commercial use.

- Best fit: complaint, review, advocacy, or satire angles
- Median ask is 10.79 across this .gripe selection
- Check if the word becomes clearer or weaker with .gripe
- Plain dictionary words usually beat obscure or awkward terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GRIPE One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GRIPE page](https://unique.domains/domains/tld/gripe?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_gripe_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
