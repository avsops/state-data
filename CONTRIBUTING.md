# Contributing to AVSOPS State Data

Thank you for helping keep veteran resource data accurate and current. This guide explains how to contribute — no coding experience required.

---

## Who Should Contribute

This repository welcomes contributions from:

- **CVSO staff** — You know your county's data better than anyone. Corrections and updates from you are the most valuable contributions we receive.
- **State DVA employees** — If your agency maintains official data, we'd welcome a direct partnership. Open an Issue labeled `state-partnership` and we'll be in touch.
- **VSO volunteers** — Post commanders, adjutants, and service officers who notice outdated information.
- **Researchers and journalists** — Anyone working with this data who finds errors or gaps.
- **Civic technologists** — Developers who want to improve data quality at scale.

---

## Ways to Contribute

### Option 1 — Report an Error (Easiest)

If you spot something wrong — a phone number changed, an officer retired, an office moved — the simplest thing to do is open a GitHub Issue.

1. Go to the [Issues tab](https://github.com/avsops/state-data/issues)
2. Click **New Issue**
3. Include: state, county, what's wrong, and the correct information
4. Submit — we'll make the fix

You don't need a GitHub account to flag an error; you can also email corrections to us via [AVSOPS.com](https://avsops.com).

---

### Option 2 — Edit a File Directly (No coding required)

If you want to fix something yourself in an existing CSV:

1. Navigate to the state folder (e.g., `IN - Indiana/`)
2. Click the CSV file you want to edit
3. Click the **pencil icon** (Edit this file) in the top right
4. Make your changes directly in the browser
5. Scroll down and click **Propose changes**
6. GitHub will walk you through opening a Pull Request

GitHub will prompt you to create a free account if you don't have one.

---

### Option 3 — Add a New State's Data (Larger contribution)

If you want to contribute a full CVSO directory or other data file for a state that doesn't have one yet:

1. Check the [State Status](https://github.com/avsops/state-data/wiki/State-Status) page to confirm the state is open
2. Review the [Data Format](https://github.com/avsops/state-data/wiki/Data-Format) page — all columns, required fields, and the geo tag format are documented there
3. Open an Issue labeled `new-state-data` so we can coordinate and avoid duplicate effort
4. Prepare your CSV following the format spec
5. Submit a Pull Request placing the file in the correct state folder

**File naming:** `{StateName}_{data_type}.csv` — for example, `Ohio_cvso.csv` or `Texas_veteran_programs.csv`.

---

## Data Standards

To keep the data consistent and usable:

- Use **UTF-8 encoding** for all CSV files
- Leave cells **empty** for missing values — do not use "N/A", "none", or dashes
- Phone numbers should include area codes: `(260) 724-5371`
- URLs should include `https://`
- Multiple values in one cell can be separated with semicolons (`;`)
- **Geo tags** follow the pattern `{state_abbrev}_{fips_code}` in lowercase — e.g., `in_18001`. FIPS codes are available at [Census.gov](https://www.census.gov/library/reference/code-lists/ansi.html).

See the full [Data Format](https://github.com/avsops/state-data/wiki/Data-Format) page for complete column specifications.

---

## Data Sources

We collect data from publicly available sources only. Acceptable sources include:

- State DVA / DVSA official websites
- County government websites
- Official VSO national and state department directories
- VA.gov and related federal resources

Please note the source URL in your Pull Request or Issue when possible. This helps us verify data and attribute it correctly.

---

## What Happens After You Submit

- **Issues** are reviewed and addressed by AVSOPS maintainers, typically within a few days
- **Pull Requests** are reviewed for formatting and data accuracy before merging
- Merged data flows into [AVSOPS.com](https://avsops.com) on the next site update

We review every contribution carefully. If something needs adjustment, we'll leave a comment explaining what to change.

---

## Questions

Open an Issue with the label `question`, or reach out through [AVSOPS.com](https://avsops.com).

This data exists to help veterans find the services they've earned. Every correction matters.
