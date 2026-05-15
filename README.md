# Sleep CSV to JSON

Converts the exported CSV file from [Sleep as Android](https://sleep.urbandroid.org/) into a human-readable JSON file.

**[Try it live on GitHub Pages](https://shelbeely.github.io/sleep-csv-to-json/)**

## Features

- Runs entirely in your browser — no data is ever uploaded to a server
- Drag-and-drop or file-picker support
- Handles all Sleep as Android CSV record types (with and without actigraphy/noise data)
- Light and dark mode support

## CSV format

See the official [Sleep as Android CSV format documentation](https://sleep.urbandroid.org/docs/devs/csv.html) for details on the fields.

## Getting your CSV file

1. Open Sleep as Android
2. Tap **☰ Menu → Backup → Export data**
3. The CSV file is at `/sleep-data/sleep-export.csv` on your device's internal storage

## Running locally

Just open `index.html` in any modern browser — no server or build step required.

## Enabling GitHub Pages

1. Go to **Settings → Pages** in this repository
2. Under **Source**, select **Deploy from a branch** or use the included **GitHub Actions** workflow
3. The site will be available at `https://<your-username>.github.io/sleep-csv-to-json/`
