# Bilim (Science)

9 datasets — 405 records

> Browse at [listbase.org/tr/science/](https://listbase.org/tr/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Kimyasal Elementler Periyodik Tablo Veri Seti](science-periodic-table.json) | 118 | 39 KB | [CSV](science-periodic-table_TR.csv) | [Excel](science-periodic-table_TR.xlsx) | [View](https://listbase.org/tr/science/science-periodic-table/) |
| [Kapsamlı RNA Kodon Tablosu Veri Seti](science-codon-table.json) | 64 | 13 KB | [CSV](science-codon-table_TR.csv) | [Excel](science-codon-table_TR.xlsx) | [View](https://listbase.org/tr/science/science-codon-table/) |
| [Elektronegatiflik Tablosu (Pauling Skalası) Veri Seti](science-electronegativity.json) | 62 | 17 KB | [CSV](science-electronegativity_TR.csv) | [Excel](science-electronegativity_TR.xlsx) | [View](https://listbase.org/tr/science/science-electronegativity/) |
| [Uluslararası Birimler Sistemi (SI Birimleri) Veri Kümesi](science-si-units.json) | 53 | 13 KB | [CSV](science-si-units_TR.csv) | [Excel](science-si-units_TR.xlsx) | [View](https://listbase.org/tr/science/science-si-units/) |
| [pH Ölçeği Referans Veri Seti ve Kimyasal Özellikler](science-ph-scale.json) | 33 | 8 KB | [CSV](science-ph-scale_TR.csv) | [Excel](science-ph-scale_TR.xlsx) | [View](https://listbase.org/tr/science/science-ph-scale/) |
| [Kapsamlı Çözünürlük Kuralları Tablosu Veri Seti](science-solubility-rules.json) | 31 | 12 KB | [CSV](science-solubility-rules_TR.csv) | [Excel](science-solubility-rules_TR.xlsx) | [View](https://listbase.org/tr/science/science-solubility-rules/) |
| [Kapsamlı Amino Asit Özellikleri Veri Seti](science-amino-acids.json) | 22 | 10 KB | [CSV](science-amino-acids_TR.csv) | [Excel](science-amino-acids_TR.xlsx) | [View](https://listbase.org/tr/science/science-amino-acids/) |
| [Kapsamlı Kan Grupları Uyumluluk Tablosu Veri Seti](science-blood-types.json) | 11 | 6 KB | [CSV](science-blood-types_TR.csv) | [Excel](science-blood-types_TR.xlsx) | [View](https://listbase.org/tr/science/science-blood-types/) |
| [Güneş Sistemi Gezegenleri ve Gök Cisimleri Veri Seti](science-planet-data.json) | 11 | 10 KB | [CSV](science-planet-data_TR.csv) | [Excel](science-planet-data_TR.xlsx) | [View](https://listbase.org/tr/science/science-planet-data/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/science/science-periodic-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/science/)
