# eUCFR Viewer

A single HTML file that turns a monthly eUCFR (`.csv`) into a step-by-step pay audit.
Open it in a browser, upload the file, and work through it. Nothing to install, all
data stays local. No internet required.

## Try it out by clicking here: https://sailbots.github.io/eUCFR_Auditor/

## What it does

**Single Audit**: Upload → pick commands → pick audits → review → report
- **Sea Pay / Sub Pay / Meal Deduction mismatches**: flags sailors whose pay doesn't
  match what their command is set to be entitled to.
- **GTC Delinquencies**: names, days delinquent, and amount owed
- **Upcoming Use-or-Lose**: sailors with leave balances over 90 days now or within the next 3 months
- **Pay Shifts**: net pay changes larger than a percentage you set
- Results grouped by command, with an "Ignore" option for reviewed mismatches
- **Reporting**: generates an email "summary" you can copy, paste and send out

**Comparison**: Upload two months to see who was added, removed, transferred, or promoted,
plus pay increases/decreases, special pays gained/lost, meal deduction and dependency changes.

**Command Editor**: A running record of every command seen, keyed by UIC: Notes, parent/child chain of command (audit a squadron and its units at once), and a dated pay entitlement log. Export/import as JSON.

## How to download & employ

1. Download `index.html`.
2. Open it in Chrome, Edge, Safari, or Firefox.
3. Click **Upload eUCFR** and follow the steps.

Handles both the raw eUCFR export and files re-saved through Excel (Excel date serials,
unformatted numbers). Separated, suspended and confined sailors are excluded automatically.

## Data

- Files are read locally; nothing is uploaded or sent anywhere.
- Settings, entitlements, and the command record are saved in your browser's local storage
  (this browser on this computer only). Use **Export** in the Command Editor to back them up.

## License

Intended for use by individual persons, federal, state and local government use. Not for commercial use.
