# ListBase CDN — Türkçe (tr)

Open dataset collection for **Türkçe** (Turkish).
508 datasets across 16 categories with 593,043 total records.

> Browse and download at [https://listbase.org/tr/](https://listbase.org/tr/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kültür & Din (Culture & Religion)](culture/) | 2 |
| [Eğitim (Education)](education/) | 170 |
| [Çevre (Environment)](environment/) | 2 |
| [Finans & Ticaret (Finance & Trade)](finance/) | 5 |
| [Gıda & Beslenme (Food & Nutrition)](food/) | 1 |
| [Coğrafya (Geography)](geography/) | 191 |
| [Dil (Language)](language/) | 5 |
| [Matematik (Mathematics)](math/) | 3 |
| [Müzik (Music)](music/) | 2 |
| [Referans (Reference)](reference/) | 46 |
| [Bilim (Science)](science/) | 9 |
| [Spor (Sports)](sports/) | 8 |
| [Teknoloji (Technology)](tech/) | 13 |
| [Zaman & Takvim (Time & Calendar)](time/) | 2 |
| [Ulaşım (Transport)](transport/) | 45 |
| [Birimler & Ölçüler (Units & Measurements)](units/) | 4 |

## Usage

### Browse on the web
Visit [listbase.org/tr/](https://listbase.org/tr/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.tr.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.tr.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.tr.listbase.org/geography/th-central-provinces_TR.xlsx
curl -O https://cdn.tr.listbase.org/geography/th-central-provinces_TR.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.tr.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.tr.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_TR.csv   # CSV download
│   └── {dataset}_TR.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
