# AASR 33 Inspector

A standalone HTML application for the **Report of the Grand Inspector** and the ongoing monitoring of attendance and administrative acts for AASR workshops.

## Live Page

Primary live page:

https://dskiad.github.io/aasr33Inspector/

Repository:

https://github.com/dskiad/aasr33Inspector

## Purpose

The page records, per meeting date:

- attendance count
- workshop name
- administrative act or ritual work
- multiple act selections
- free-text notes and descriptions

It is designed for the workshops:

- **«Μυσταγωγία» υπ' αρ. 5**
- **«Φως» υπ' αρ. 14**

## Preloaded Dates

### «Μυσταγωγία» υπ' αρ. 5

- 4 November 2026
- 2 December 2026
- 3 February 2027
- 3 March 2027
- 7 April 2027
- 5 May 2027

### «Φως» υπ' αρ. 14

- 13 October 2026
- 10 November 2026
- 8 December 2026
- 12 January 2027
- 9 February 2027
- 9 March 2027
- 13 April 2027
- 11 May 2027

## Administrative Act Options

Each date supports multiple selections from:

- Μύηση
- Ομιλία
- Ψηφοφορία
- Εγκατάσταση
- Διοικητική ενημέρωση
- Άλλη πράξη

There is also a free-text field for any additional act or description.

## Features

- Preloaded meeting calendar
- Attendance count per date
- Multiple administrative act choices
- Free-text description field
- Filters by workshop and act type
- Search field
- Automatic local browser saving
- CSV export
- JSON export and import
- Print / Save as PDF
- Mobile-friendly layout

## Data Storage

The app stores entries locally in the browser using `localStorage`.

For backup or transfer to another device, use:

- **Export JSON** for full backup and later import
- **Export CSV** for spreadsheet/reporting use

## Deployment

The repository includes a GitHub Actions workflow:

`.github/workflows/pages.yml`

This workflow deploys the static site to GitHub Pages from the `main` branch.

If Pages is not active, enable it from:

**Repository Settings > Pages > Build and deployment > GitHub Actions**

Then run the workflow or push a new commit to `main`.
