# Available .TAX One-Word Domains (15,475)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C475%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tax one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,475 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,475 domains · **Median ask:** $17.29 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-16
**Canonical page:** `https://unique.domains/domains/tld/tax`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tax?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tax.csv">CSV</a> / <a href="./tax.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TAX search](https://unique.domains/domains/tld/tax?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TAX search](https://unique.domains/domains/tld/tax?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TAX one-word domain catalog.

### Files

- `tax.csv`, public CSV extract (1,000 rows)
- `tax.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tax-oneword-domains/main/tax.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| bow.tax   | available | $14.99    | —             | high           | low    | 3      | name.com                                            |
| act.tax   | resell    | —         | —             | high           | low    | 3      | Chengdu West Dimension Digital Technology Co., Ltd. |
| dog.tax   | premium   | $250      | —             | high           | low    | 3      | name.com                                            |
| CNN.tax   | available | $14.99    | —             | high           | low    | 3      | name.com                                            |
| arc.tax   | resell    | —         | —             | medium         | medium | 3      | DNSPod, Inc.                                        |
| arab.tax  | premium   | $118.80   | $118.80       | low            | low    | 4      | namesilo                                            |
| coy.tax   | available | $14.99    | $92.99        | medium         | low    | 3      | name.com                                            |
| our.tax   | resell    | —         | —             | medium         | medium | 3      | DNSPod, Inc.                                        |
| post.tax  | premium   | $854      | $854          | high           | medium | 4      | namesilo                                            |
| cue.tax   | available | $14.99    | —             | medium         | low    | 3      | name.com                                            |
| sun.tax   | resell    | —         | —             | high           | medium | 3      | DNSPod, Inc.                                        |
| adult.tax | premium   | $123.75   | $123.75       | high           | low    | 5      | name.com                                            |
| don.tax   | available | $14.99    | —             | high           | low    | 3      | name.com                                            |
| wiz.tax   | resell    | —         | —             | high           | low    | 3      | Xiamen ChinaSource Internet Service Co., Ltd        |
| great.tax | premium   | $242      | $242          | high           | low    | 5      | namesilo                                            |
| eye.tax   | available | $14.99    | —             | medium         | low    | 3      | name.com                                            |
| arch.tax  | resell    | —         | —             | medium         | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd        |
| promo.tax | premium   | $123.75   | —             | high           | low    | 5      | name.com                                            |
| far.tax   | available | $14.99    | —             | high           | low    | 3      | name.com                                            |
| axis.tax  | resell    | —         | —             | medium         | medium | 4      | Sav.com, LLC - 16                                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,475 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tax?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tax?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These are one-word .TAX domain names, each built from a single continuous string like getlife, primarycare, or headout, then paired with the .TAX extension. With 11,887 domains in this set and a median ask near $22, pricing stays accessible across the board. The .TAX extension signals financial, accounting, or advisory relevance, making these names easy to position for tax-prep firms, bookkeeping services, or fintech products. When comparing these domains, weigh string length, clarity, and how directly the word or phrase reads in a tax or finance context.

- 11,887 one-word .TAX domains in this set
- Median asking price around $22
- Single continuous strings, no hyphens or numbers
- Clear fit for tax, accounting & advisory branding

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TAX One-Word Domains*. Version 2026-08-16. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TAX page](https://unique.domains/domains/tld/tax?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tax_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
