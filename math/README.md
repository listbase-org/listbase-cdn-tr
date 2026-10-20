# Matematik (Mathematics)

3 datasets — 152 records

> Browse at [listbase.org/tr/math/](https://listbase.org/tr/math/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Türev Formülleri ve Kuralları Veri Seti](math-derivative-formulas.json) | 57 | 12 KB | [CSV](math-derivative-formulas_TR.csv) | [Excel](math-derivative-formulas_TR.xlsx) | [View](https://listbase.org/tr/math/math-derivative-formulas/) |
| [Yaygın Entegrasyon Formülleri Veri Kümesi](math-integral-formulas.json) | 56 | 13 KB | [CSV](math-integral-formulas_TR.csv) | [Excel](math-integral-formulas_TR.xlsx) | [View](https://listbase.org/tr/math/math-integral-formulas/) |
| [Kapsamlı Laplace Dönüşüm Tablosu Veri Kümesi](math-laplace-transform.json) | 39 | 9 KB | [CSV](math-laplace-transform_TR.csv) | [Excel](math-laplace-transform_TR.xlsx) | [View](https://listbase.org/tr/math/math-laplace-transform/) |

## Quick Start

```bash
# List all mathematics datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="math") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/math/math-derivative-formulas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/math/)
