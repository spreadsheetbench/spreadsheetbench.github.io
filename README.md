# SpreadsheetBench Homepage

Home page of SpreadsheetBench.

## Run

Open `index.html` in a browser.

Or start a local server:

```bash
python -m http.server 8000
```

Open http://localhost:8000/

## Updating leaderboards

Leaderboard data is stored in `data/leaderboard-v1-full.json`, `data/leaderboard-v1-verified.json`, and `data/leaderboard-v2-full.json`. Add a new object to the appropriate file, using an existing entry as a template.

Every leaderboard is automatically sorted by score (highest first), then date (oldest first for tied scores), with ranks generated on the page.

The website template is from Nerfies.
