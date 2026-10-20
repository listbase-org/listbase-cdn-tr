# Gıda & Beslenme (Food & Nutrition)

1 datasets — 167 records

> Browse at [listbase.org/tr/food/](https://listbase.org/tr/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Türkiye'deki Michelin Restoranları](tr-michelin-restoranlari.json) | 167 | 215 KB | [CSV](tr-michelin-restoranlari_TR.csv) | [Excel](tr-michelin-restoranlari_TR.xlsx) | [View](https://listbase.org/tr/food/tr-michelin-restoranlari/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/food/tr-michelin-restoranlari.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/food/)
