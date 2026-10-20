# Dil (Language)

5 datasets — 593 records

> Browse at [listbase.org/tr/language/](https://listbase.org/tr/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Çince Pinyin Heceleri Tablosu ve Telaffuz Rehberi](lang-pinyin-table.json) | 408 | 101 KB | [CSV](lang-pinyin-table_TR.csv) | [Excel](lang-pinyin-table_TR.xlsx) | [View](https://listbase.org/tr/language/lang-pinyin-table/) |
| [İngilizce Zamir Sınıflandırma Tablosu Veri Seti](lang-english-pronouns.json) | 69 | 20 KB | [CSV](lang-english-pronouns_TR.csv) | [Excel](lang-english-pronouns_TR.xlsx) | [View](https://listbase.org/tr/language/lang-english-pronouns/) |
| [Japonca Hiragana Tablosu ve Romaji Eşleme Veri Seti](lang-hiragana-table.json) | 46 | 11 KB | [CSV](lang-hiragana-table_TR.csv) | [Excel](lang-hiragana-table_TR.xlsx) | [View](https://listbase.org/tr/language/lang-hiragana-table/) |
| [Eksiksiz Japonca Katakana Karakter Tablosu Veri Seti](lang-katakana-table.json) | 46 | 11 KB | [CSV](lang-katakana-table_TR.csv) | [Excel](lang-katakana-table_TR.xlsx) | [View](https://listbase.org/tr/language/lang-katakana-table/) |
| [Tam Yunan Alfabesi Karakterleri Veri Seti](lang-greek-alphabet.json) | 24 | 9 KB | [CSV](lang-greek-alphabet_TR.csv) | [Excel](lang-greek-alphabet_TR.xlsx) | [View](https://listbase.org/tr/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/language/lang-pinyin-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/language/)
