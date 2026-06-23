# jsonloc

Browser-based JSON localization editor. Load a source and target JSON file side by side, edit translations, and save when done. No server, no install — open the HTML file and go.

**[yigithal.github.io/jsonloc](https://yigithal.github.io/jsonloc/)**

## Usage

1. Open `index.html` in a browser
2. Drop or click **Source JSON** to load the reference file
3. Drop or click **Target JSON** to load the file you are translating into
4. Edit translations in the right column
5. Save the target file when done

## Features

- Side-by-side editor with key path, source, and target columns
- Status badges: missing keys, empty values, extra keys, type mismatches, exact matches
- Length warning when a translation exceeds 1.5× the source character count
- Placeholder detection — highlights `{{name}}`, `%s`, `{key}` and flags missing or extra ones
- Special character warnings for `< > " & \``
- Regex support in the filter bar (`/pattern/flags`)
- CSV export with key, source, target, and max-characters columns
- Export/import missing translations as a JSON snippet for external translators
- Dark and light theme, saved to localStorage
- Session history log
- Keyboard shortcuts: `Ctrl+S` to save, `Ctrl+Enter` to move to next field, `F8` to jump to next untranslated item

## License

Free for personal use. For commercial use, contact [yigithal@gmail.com](mailto:yigithal@gmail.com).

© 2026 Hal Yigit — [linkedin.com/in/yigithal](https://www.linkedin.com/in/yigithal/)
