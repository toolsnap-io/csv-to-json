# CSV to JSON Converter 📊

Convert CSV data to JSON format instantly. The fastest way to transform spreadsheet data into structured JSON objects.

## ✨ Features

- **Instant conversion** — Paste CSV, get JSON in real-time
- **Auto-detection** — Smart delimiter detection (comma, semicolon, tab)
- **Header parsing** — First row automatically becomes JSON keys
- **Custom headers** — Override auto-detected headers
- **Format options** — Minified or pretty-printed JSON output
- **Error handling** — Clear error messages for malformed CSV
- **Download** — Save converted JSON as a file
- **Large file support** — Handles thousands of rows smoothly

## 🚀 Try It Online

👉 **[Use CSV to JSON on ToolSnap](https://risetop.top/csv-to-json.html)**

## 📖 Usage

1. Visit [risetop.top/csv-to-json.html](https://risetop.top/csv-to-json.html)
2. Paste your CSV data or upload a `.csv` file
3. Configure options (delimiter, indentation)
4. Copy or download the resulting JSON

### Example

**Input CSV:**
```csv
name,email,role
Alice,alice@example.com,Admin
Bob,bob@example.com,User
Charlie,charlie@example.com,Editor
```

**Output JSON:**
```json
[
  { "name": "Alice", "email": "alice@example.com", "role": "Admin" },
  { "name": "Bob", "email": "bob@example.com", "role": "User" },
  { "name": "Charlie", "email": "charlie@example.com", "role": "Editor" }
]
```

## 🔧 Use Cases

- **API development** — Convert test data from spreadsheets to JSON
- **Data migration** — Transform CSV exports to JSON imports
- **Configuration files** — Convert tabular data to JSON config
- **Database seeding** — Generate JSON fixtures from CSV data
- **Data analysis** — Quick format conversion for data pipelines

## 📋 Supported Formats

| Input | Output |
|-------|--------|
| CSV (comma) | JSON Array |
| TSV (tab) | JSON Array |
| SSV (semicolon) | JSON Array |
| Custom delimiter | JSON Array |

## 🛠 Technical Details

- RFC 4180 compliant CSV parsing
- Handles quoted fields, escaped quotes, and newlines within fields
- Streaming parser for large files
- Zero dependencies, browser-native implementation

## 📄 License

MIT License — feel free to use in your projects.

---

**[ToolSnap](https://risetop.top)** — Free online tools for developers.
