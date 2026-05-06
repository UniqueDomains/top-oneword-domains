# Available .TOP One-Word Domains (9,678)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C678%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .top one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,678 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,678 domains · **Median ask:** $1,216.28 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `top.csv` — public CSV extract (1,000 rows)
- `top.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/top-oneword-domains/main/top.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| barup.top         | available | $6.98     | —             | 82             | 2      | 6      | namecheap       |
| dogsit.top        | available | $6.98     | —             | 96             | 2      | 6      | namecheap       |
| QandA.top         | available | $6.98     | —             | 80             | 10     | 7      | namecheap       |
| croptop.top       | available | $6.98     | —             | 80             | 4      | 8      | namecheap       |
| presents.top      | available | $6.98     | —             | 80             | 9      | 8      | namecheap       |
| fitinto.top       | available | $6.98     | —             | 84             | 2      | 8      | namecheap       |
| chaitea.top       | available | $6.98     | —             | 86             | 3      | 8      | namecheap       |
| makenews.top      | available | $6.98     | —             | 80             | 1      | 9      | namecheap       |
| becalled.top      | available | $1.88     | $4.88         | 86             | 2      | 9      | namesilo        |
| turninto.top      | available | $6.98     | —             | 86             | 2      | 9      | namecheap       |
| letitbe.top       | available | $6.98     | —             | 89             | 7      | 9      | namecheap       |
| fasttimes.top     | available | $6.98     | —             | 80             | 3      | 10     | namecheap       |
| makewhole.top     | available | $6.98     | —             | 80             | 2      | 10     | namecheap       |
| keepthechange.top | available | $6.98     | —             | 46             | 59     | 15     | namecheap       |
| robots.top        | resell    | —         | —             | 62             | 47     | 6      | Spaceship, Inc. |
| donuts.top        | premium   | $91.43    | —             | 54             | 62     | 6      | name.com        |
| stadia.top        | available | $6.98     | —             | 66             | 22     | 6      | namecheap       |
| coins.top         | resell    | —         | —             | 56             | 41     | 5      | 西部数码国际有限公司      |
| justin.top        | premium   | $91.45    | —             | 58             | 38     | 7      | name.com        |
| techsupport.top   | available | $6.98     | —             | 76             | 18     | 12     | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,678 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/top?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/top?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=related_pricing)

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

This selection is focused entirely on one-word .top domains. The set includes literal words, phrase-like compounds, and conversational forms such as edamame.top, dogsit.top, QandA.top, getlife.top, and presents.top. For founders, the main question is whether the word is memorable, easy to say, and specific enough to support a real brand. For investors, the key test is whether the ask leaves room for a reasonable spread relative to how broadly the word can appeal. The median ask is $1,216, so stronger names should justify that level with clarity, recognizability, and clean commercial use.

- Prioritize clear words over awkward or confusing constructions
- Check if the ask fits the word's breadth and resale potential
- Favor names that sound natural when spoken aloud
- Review spelling, capitalization, and possible trademark friction

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TOP One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TOP page](https://unique.domains/domains/tld/top?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_top_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
