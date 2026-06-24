# jsonloc

Browser-based JSON localization editor. Load a source and target JSON file side by side, edit translations, and save when done. Everything runs in the browser.

**[yigithal.github.io/jsonloc](https://yigithal.github.io/jsonloc/)**

## Usage

1. Open `index.html` in a browser or visit [yigithal.github.io/jsonloc](https://yigithal.github.io/jsonloc/)
2. Drop or click **Source JSON** to load the reference file
3. Drop or click **Target JSON** to load the file you are translating into
4. Edit translations in the right column
5. Save the target file when done

## Features

- Side-by-side editor with key path, source, and target columns
- Status badges for missing keys, empty values, extra keys, type mismatches, and exact matches
- Length warning when target exceeds a configurable threshold (default 1.5x)
- Placeholder detection for `{{name}}`, `%s`, `{key}` — flags missing or extra ones
- ICU plural/select support: edit each case in its own field, validate coverage and variables, add extra cases (e.g. `few`, `many`)
- Filter with regex, with status filters, search and replace with undo
- CSV export with max-characters column; export/import missing keys as JSON
- Correctly handles dotted key names (e.g. `"error.code"` vs nested `error → code`)
- Preserves indentation, line endings, and BOM on export
- Dark/light theme, session history, keyboard shortcuts

## License

Free for personal use. For commercial use, contact [yigithal@gmail.com](mailto:yigithal@gmail.com).

© 2026 Hal Yigit | [linkedin.com/in/yigithal](https://www.linkedin.com/in/yigithal/)
