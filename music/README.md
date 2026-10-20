# Müzik (Music)

2 datasets — 162 records

> Browse at [listbase.org/tr/music/](https://listbase.org/tr/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kapsamlı Piyano Akor Tablosu Referans Veri Seti](music-piano-chords.json) | 84 | 22 KB | [CSV](music-piano-chords_TR.csv) | [Excel](music-piano-chords_TR.xlsx) | [View](https://listbase.org/tr/music/music-piano-chords/) |
| [Kapsamlı Gitar Akor Tablosu Veri Seti](music-guitar-chords.json) | 78 | 24 KB | [CSV](music-guitar-chords_TR.csv) | [Excel](music-guitar-chords_TR.xlsx) | [View](https://listbase.org/tr/music/music-guitar-chords/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.tr.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.tr.listbase.org/music/music-piano-chords.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/tr/music/)
