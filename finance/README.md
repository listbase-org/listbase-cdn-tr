# Finans & Ticaret (Finance & Trade)

5 datasets — 324 records

> Browse at [listbase.org/tr/finance/](https://listbase.org/tr/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [GS1 Barkod Ön Eki ve Ülke Kodu Kayıt Veri Seti](finance-gs1-codes.json) | 126 | 19 KB | [CSV](finance-gs1-codes_TR.csv) | [Excel](finance-gs1-codes_TR.xlsx) | [View](https://listbase.org/tr/finance/finance-gs1-codes/) |
| [HS Kodu (Armonize Sistem) Bölümleri Veri Kümesi](finance-hs-codes.json) | 98 | 22 KB | [CSV](finance-hs-codes_TR.csv) | [Excel](finance-hs-codes_TR.xlsx) | [View](https://listbase.org/tr/finance/finance-hs-codes/) |
| [Kapsamlı Ülkelere Göre KDV/ÖTV Oranları Veri Seti](finance-vat-rates.json) | 75 | 18 KB | [CSV](finance-vat-rates_TR.csv) | [Excel](finance-vat-rates_TR.xlsx) | [View](https://listbase.org/tr/finance/finance-vat-rates/) |
| [ISO 6346 Nakliye Konteyner Kodları ve Özellikleri Veri Kümesi](finance-container-codes.json) | 14 | 8 KB | [CSV](finance-container-codes_TR.csv) | [Excel](finance-container-codes_TR.xlsx) | [View](https://listbase.org/tr/finance/finance-container-codes/) |
| [Incoterms 2020 Kuralları ve Tanımları Veri Seti](finance-incoterms.json) | 11 | 8 KB | [CSV](finance-incoterms_TR.csv) | [Excel](finance-incoterms_TR.xlsx) | [View](https://listbase.org/tr/finance/finance-incoterms/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/finance/finance-gs1-codes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/finance/)
