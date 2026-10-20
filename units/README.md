# Birimler & Ölçüler (Units & Measurements)

4 datasets — 216 records

> Browse at [listbase.org/tr/units/](https://listbase.org/tr/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Birim Dönüşüm Faktörleri Veri Seti](units-conversions.json) | 83 | 16 KB | [CSV](units-conversions_TR.csv) | [Excel](units-conversions_TR.xlsx) | [View](https://listbase.org/tr/units/units-conversions/) |
| [Temperature Conversion Matrix Dataset](units-temperatures.json) | 55 | 11 KB | [CSV](units-temperatures_TR.csv) | [Excel](units-temperatures_TR.xlsx) | [View](https://listbase.org/tr/units/units-temperatures/) |
| [Uluslararası Ayakkabı Beden Dönüşüm Tablosu Veri Seti](units-shoe-sizes.json) | 43 | 8 KB | [CSV](units-shoe-sizes_TR.csv) | [Excel](units-shoe-sizes_TR.xlsx) | [View](https://listbase.org/tr/units/units-shoe-sizes/) |
| [Clothing Size Standards Dataset](units-clothing-sizes.json) | 35 | 10 KB | [CSV](units-clothing-sizes_TR.csv) | [Excel](units-clothing-sizes_TR.xlsx) | [View](https://listbase.org/tr/units/units-clothing-sizes/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/units/units-conversions.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/units/)
