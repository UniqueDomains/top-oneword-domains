# Available .TOP One-Word Domains (9,702)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C702%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .top one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,702 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,702 domains · **Median ask:** $869.21 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/top`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/top?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./top.csv">CSV</a> / <a href="./top.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TOP search](https://unique.domains/domains/tld/top?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TOP search](https://unique.domains/domains/tld/top?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TOP one-word domain catalog.

### Files

- `top.csv`, public CSV extract (1,000 rows)
- `top.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/top-oneword-domains/main/top.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| erupt.top | available | $1.88     | $4.88         | high           | low    | 5      | namesilo       |
| golf.top  | resell    | —         | —             | high           | medium | 4      | 阿里云计算有限公司      |
| ago.top   | premium   | $363.54   | $363.54       | medium         | low    | 3      | name.com       |
| fewer.top | available | $1.88     | $4.88         | medium         | low    | 5      | namesilo       |
| snap.top  | resell    | —         | —             | high           | medium | 4      | 阿里云计算有限公司      |
| are.top   | premium   | $5,019.37 | —             | high           | low    | 3      | name.com       |
| froze.top | available | $1.88     | $4.88         | medium         | low    | 5      | namesilo       |
| wine.top  | resell    | —         | —             | high           | low    | 4      | 阿里云计算有限公司      |
| bed.top   | premium   | $915.30   | —             | high           | low    | 3      | name.com       |
| holes.top | available | $1.88     | $4.88         | medium         | low    | 5      | namesilo       |
| bonus.top | resell    | —         | —             | high           | low    | 5      | 阿里云计算有限公司      |
| bud.top   | premium   | $91.50    | —             | high           | low    | 3      | name.com       |
| orso.top  | available | $6.98     | —             | medium         | low    | 5      | namecheap      |
| chain.top | resell    | —         | —             | medium         | low    | 5      | 成都西维数码科技有限公司   |
| err.top   | premium   | $91.90    | —             | high           | low    | 3      | name.com       |
| Ropes.top | available | $1.88     | $4.88         | medium         | low    | 5      | namesilo       |
| shoes.top | resell    | —         | —             | high           | low    | 5      | 成都西维数码科技有限公司   |
| fat.top   | premium   | $914.07   | —             | medium         | low    | 3      | name.com       |
| shush.top | available | $1.88     | $4.88         | medium         | low    | 5      | namesilo       |
| snack.top | resell    | —         | —             | high           | low    | 5      | Namecheap Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,702 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/top?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/top?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=related_pricing)

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

This list of one-word .top domains spans 9,702 names with a median ask around $869.21, giving founders and investors a broad set of brandable, single-word options to compare. Names like dogsit.top, video.top, and pictures.top show how the .top extension pairs short, everyday words into memorable domain names. Because pricing varies widely across this set, comparing ask price against the word's clarity, length, and industry fit is the fastest way to separate strong picks from the rest.

- 9,702 one-word .top domain names in this selection
- Median ask near $869.21 across the set
- Short, everyday words paired into brandable names
- Spans many industries, from tech to lifestyle terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TOP One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TOP page](https://unique.domains/domains/tld/top?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
