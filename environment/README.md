# Çevre (Environment)

2 datasets — 171 records

> Browse at [listbase.org/tr/environment/](https://listbase.org/tr/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Türkiye'deki elektrik santralleri](tr-elektrik-santralleri.json) | 163 | 60 KB | [CSV](tr-elektrik-santralleri_TR.csv) | [Excel](tr-elektrik-santralleri_TR.xlsx) | [View](https://listbase.org/tr/environment/tr-elektrik-santralleri/) |
| [Türkiye'deki nükleer santraller](tr-nukleer-santraller.json) | 8 | 6 KB | [CSV](tr-nukleer-santraller_TR.csv) | [Excel](tr-nukleer-santraller_TR.xlsx) | [View](https://listbase.org/tr/environment/tr-nukleer-santraller/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/environment/tr-elektrik-santralleri.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/environment/)
