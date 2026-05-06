# Available .CV One-Word Domains (12,071)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C071%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cv one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,071 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,071 domains · **Median ask:** $115.23 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/cv`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cv?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cv.csv">CSV</a> / <a href="./cv.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CV search](https://unique.domains/domains/tld/cv?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CV search](https://unique.domains/domains/tld/cv?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CV one-word domain catalog.

### Files

- `cv.csv` — public CSV extract (1,000 rows)
- `cv.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cv-oneword-domains/main/cv.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| pierogi.cv      | available | $14.98    | —             | 82             | 7      | 7      | namecheap |
| getlife.cv      | available | $14.98    | —             | 80             | 5      | 8      | namecheap |
| leaveon.cv      | available | $14.98    | —             | 80             | 1      | 8      | namecheap |
| fitinto.cv      | available | $14.98    | —             | 84             | 2      | 8      | namecheap |
| keepfit.cv      | available | $14.98    | —             | 86             | 9      | 8      | namecheap |
| dogstail.cv     | available | $14.98    | —             | 94             | 1      | 8      | namecheap |
| backyard.cv     | available | $14.98    | —             | 80             | 27     | 9      | namecheap |
| bedframe.cv     | available | $14.98    | —             | 80             | 3      | 9      | namecheap |
| flaxseed.cv     | available | $14.98    | —             | 80             | 4      | 9      | namecheap |
| cometrue.cv     | available | $14.98    | —             | 82             | 5      | 9      | namecheap |
| getiton.cv      | available | $14.98    | —             | 84             | 3      | 9      | namecheap |
| getlucky.cv     | available | $14.98    | —             | 84             | 10     | 9      | namecheap |
| turninto.cv     | available | $14.98    | —             | 86             | 2      | 9      | namecheap |
| neuroscience.cv | available | $14.98    | —             | 80             | 37     | 12     | namecheap |
| farmers.cv      | resell    | —         | —             | 54             | 59     | 7      | Dynadot   |
| Chanel.cv       | premium   | $150.50   | $10.50        | 80             | 77     | 6      | namecheap |
| united.cv       | resell    | —         | —             | 74             | 41     | 6      | Dynadot   |
| cars.cv         | premium   | $710.50   | $94.50        | 66             | 47     | 4      | namecheap |
| coupons.cv      | available | $9.99     | $9.99         | 52             | 24     | 7      | namesilo  |
| vertical.cv     | resell    | —         | —             | 70             | 33     | 8      | Dynadot   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,071 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cv?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cv?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of .cv domains, with a wide mix of dictionary words, phrases, food terms, lifestyle terms, and brandable combinations such as edamame.cv, pierogi.cv, watches.cv, getlife.cv, and lightup.cv. For founders, the main question is whether a name is memorable, easy to say, and specific enough to own with confidence. For investors, the focus is whether the ask leaves room for a sensible deal and whether the word has broad buyer appeal. Median ask is 115.23, which makes price discipline important, but naming quality still matters more than volume alone.

- All names in this selection use the .cv extension
- Median ask across the set is 115.23
- Styles range from dictionary words to phrase brands
- Check wording for memorability and trademark friction

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CV One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CV page](https://unique.domains/domains/tld/cv?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cv_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
