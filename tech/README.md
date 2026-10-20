# Teknoloji (Technology)

13 datasets — 925 records

> Browse at [listbase.org/tr/tech/](https://listbase.org/tr/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [ISO 639 Dil Kodları ve Yerel Adlar Veri Kümesi](tech-language-codes.json) | 183 | 25 KB | [CSV](tech-language-codes_TR.csv) | [Excel](tech-language-codes_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-language-codes/) |
| [Eksiksiz ASCII Karakter Tablosu ve Kodları Referans Veri Kümesi](tech-ascii-table.json) | 128 | 28 KB | [CSV](tech-ascii-table_TR.csv) | [Excel](tech-ascii-table_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-ascii-table/) |
| [Windows ve macOS için Evrensel Klavye Kısayolları Veri Seti](tech-keyboard-shortcuts.json) | 77 | 16 KB | [CSV](tech-keyboard-shortcuts_TR.csv) | [Excel](tech-keyboard-shortcuts_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-keyboard-shortcuts/) |
| [HTML Karakter Varlıkları ve Özel Semboller Veri Kümesi](tech-html-entities.json) | 75 | 17 KB | [CSV](tech-html-entities_TR.csv) | [Excel](tech-html-entities_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-html-entities/) |
| [Ortak Ağ Port Numaraları ve Hizmetleri Veri Seti](tech-port-numbers.json) | 73 | 15 KB | [CSV](tech-port-numbers_TR.csv) | [Excel](tech-port-numbers_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-port-numbers/) |
| [Ortak MIME Türleri ve Dosya Uzantıları Veri Seti](tech-mime-types.json) | 70 | 13 KB | [CSV](tech-mime-types_TR.csv) | [Excel](tech-mime-types_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-mime-types/) |
| [Yaygın Unicode Sembolleri ve HTML Varlıkları Veri Kümesi](tech-unicode-symbols.json) | 70 | 14 KB | [CSV](tech-unicode-symbols_TR.csv) | [Excel](tech-unicode-symbols_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-unicode-symbols/) |
| [HTTP Status Codes Dataset](tech-http-codes.json) | 62 | 15 KB | [CSV](tech-http-codes_TR.csv) | [Excel](tech-http-codes_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-http-codes/) |
| [Temel Düzenli İfade Desenleri Veri Kümesi](tech-regex-patterns.json) | 45 | 12 KB | [CSV](tech-regex-patterns_TR.csv) | [Excel](tech-regex-patterns_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-regex-patterns/) |
| [Sosyal Medya Resim Boyutları ve Ölçüleri Veri Kümesi](tech-social-media-sizes.json) | 42 | 12 KB | [CSV](tech-social-media-sizes_TR.csv) | [Excel](tech-social-media-sizes_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-social-media-sizes/) |
| [Screen Resolutions & Aspect Ratios Dataset](tech-screen-resolutions.json) | 35 | 9 KB | [CSV](tech-screen-resolutions_TR.csv) | [Excel](tech-screen-resolutions_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-screen-resolutions/) |
| [Kağıt Boyutları ve Piksel Boyutları Veri Seti](tech-paper-sizes.json) | 33 | 13 KB | [CSV](tech-paper-sizes_TR.csv) | [Excel](tech-paper-sizes_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-paper-sizes/) |
| [Mantık Kapıları Doğruluk Tabloları Veri Seti](tech-logic-gates.json) | 32 | 9 KB | [CSV](tech-logic-gates_TR.csv) | [Excel](tech-logic-gates_TR.xlsx) | [View](https://listbase.org/tr/tech/tech-logic-gates/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/tech/tech-language-codes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/tech/)
