# Kültür & Din (Culture & Religion)

2 datasets — 115 records

> Browse at [listbase.org/tr/culture/](https://listbase.org/tr/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Türkiye'deki müzeler (Museums in Turkey)](tr-muzeler.json) | 97 | 22 KB | [CSV](tr-muzeler_TR.csv) | [Excel](tr-muzeler_TR.xlsx) | [View](https://listbase.org/tr/culture/tr-muzeler/) |
| [Türkiye'deki UNESCO Dünya Mirası Alanları](tr-dunya-mirasi-alanlari-unesco.json) | 18 | 20 KB | [CSV](tr-dunya-mirasi-alanlari-unesco_TR.csv) | [Excel](tr-dunya-mirasi-alanlari-unesco_TR.xlsx) | [View](https://listbase.org/tr/culture/tr-dunya-mirasi-alanlari-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/culture/tr-muzeler.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/culture/)
