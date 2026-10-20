# Zaman & Takvim (Time & Calendar)

2 datasets — 24 records

> Browse at [listbase.org/tr/time/](https://listbase.org/tr/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Çin Zodyak Hayvanları Veri Seti (12 Burç)](time-chinese-zodiac.json) | 12 | 11 KB | [CSV](time-chinese-zodiac_TR.csv) | [Excel](time-chinese-zodiac_TR.xlsx) | [View](https://listbase.org/tr/time/time-chinese-zodiac/) |
| [Kapsamlı Batı Burçları Veri Seti](time-zodiac-signs.json) | 12 | 9 KB | [CSV](time-zodiac-signs_TR.csv) | [Excel](time-zodiac-signs_TR.xlsx) | [View](https://listbase.org/tr/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/time/time-chinese-zodiac.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/time/)
