# Spor (Sports)

8 datasets — 107 records

> Browse at [listbase.org/tr/sports/](https://listbase.org/tr/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Türkiye Süper Lig ve 1. Lig Kulüpleri (Turkish Super League & 1st League Clubs)](tr-tff-kulupleri.json) | 38 | 16 KB | [CSV](tr-tff-kulupleri_TR.csv) | [Excel](tr-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-tff-kulupleri/) |
| [Türkiye Futbol Stadyumları (Turkish Football Stadiums)](tr-tff-stadyumlari.json) | 38 | 15 KB | [CSV](tr-tff-stadyumlari_TR.csv) | [Excel](tr-tff-stadyumlari_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-tff-stadyumlari/) |
| [İST./MARMARA Bölgesi Futbol Kulüpleri (İST./MARMARA Region Football Clubs)](tr-ist-marmara-tff-kulupleri.json) | 9 | 6 KB | [CSV](tr-ist-marmara-tff-kulupleri_TR.csv) | [Excel](tr-ist-marmara-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-ist-marmara-tff-kulupleri/) |
| [ANKARA Bölgesi Futbol Kulüpleri (ANKARA Region Football Clubs)](tr-ankara-tff-kulupleri.json) | 6 | 4 KB | [CSV](tr-ankara-tff-kulupleri_TR.csv) | [Excel](tr-ankara-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-ankara-tff-kulupleri/) |
| [İZMİR Bölgesi Futbol Kulüpleri (İZMİR Region Football Clubs)](tr-izmir-tff-kulupleri.json) | 6 | 4 KB | [CSV](tr-izmir-tff-kulupleri_TR.csv) | [Excel](tr-izmir-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-izmir-tff-kulupleri/) |
| [BURSA/MARMARA Bölgesi Futbol Kulüpleri (BURSA/MARMARA Region Football Clubs)](tr-bursa-marmara-tff-kulupleri.json) | 4 | 4 KB | [CSV](tr-bursa-marmara-tff-kulupleri_TR.csv) | [Excel](tr-bursa-marmara-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-bursa-marmara-tff-kulupleri/) |
| [ADANA Bölgesi Futbol Kulüpleri (ADANA Region Football Clubs)](tr-adana-tff-kulupleri.json) | 3 | 3 KB | [CSV](tr-adana-tff-kulupleri_TR.csv) | [Excel](tr-adana-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-adana-tff-kulupleri/) |
| [TRABZON Bölgesi Futbol Kulüpleri (TRABZON Region Football Clubs)](tr-trabzon-tff-kulupleri.json) | 3 | 3 KB | [CSV](tr-trabzon-tff-kulupleri_TR.csv) | [Excel](tr-trabzon-tff-kulupleri_TR.xlsx) | [View](https://listbase.org/tr/sports/tr-trabzon-tff-kulupleri/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/sports/tr-tff-kulupleri.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/sports/)
