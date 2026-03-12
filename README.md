<p align="center">
    <img src="https://avsops.com/images/avsops-logo.png" alt="AVSOPS Logo" width="300">
</p>
# AVSOPS State Data

**Public veteran resource data for all 50 U.S. states + DC — powered by [AVSOPS.com](https://avsops.com)**

---

This repository is the open data backbone of [AVSOPS.com](https://avsops.com) — The Veterans & Patriots Network. It contains publicly sourced contact directories, office locations, and benefit program information for veteran service organizations and county veteran service officers (CVSOs) across the United States.

The data is free to use, verify, and improve. State DVA offices, CVSO staff, VSO volunteers, researchers, and civic technologists are all welcome to contribute.

## Why This Exists

My father served in the Marine Corps during the Korean War, then spent 26 years at the Veterans Administration — including through its transition to a Cabinet-level department. That history is part of why I built AVSOPS: to make it easier for veterans and their families to find the local services and organizations that exist to help them.

A national veteran resource directory is only as good as its data. By making this data open and collaborative, we can keep it accurate and current in a way no single organization can do alone.

## What's in This Repository

Each state and DC has its own directory. Data files follow a consistent CSV format documented in the [Data Format wiki page](https://github.com/avsops/state-data/wiki/Data-Format).

### Data Types

| Type | File Pattern | Description |
|------|-------------|-------------|
| CVSO Directory | `{State}_cvso.csv` | County Veteran Service Officer contact info |
| State VA Offices | `{State}_va_offices.csv` | Regional VA office locations and hours |
| Veteran Programs | `{State}_veteran_programs.csv` | State-specific benefits and programs |

### Coverage Status

All 50 states + DC have directories. See the [State Status](https://github.com/avsops/state-data/wiki/State-Status) page for a full breakdown of which states have collected data.

## How to Use This Data

The data is published under [Creative Commons Attribution 4.0 (CC BY 4.0)](LICENSE.md). You're free to use, share, and build on it — just credit AVSOPS.com.

Researchers, journalists, state agencies, and developers: if you're using this data for something, we'd love to know. Open an Issue or reach out at [avsops.com](https://avsops.com).

## How to Contribute

We welcome contributions from anyone with knowledge of veteran services in their state — CVSO staff, post commanders, adjutants, VSO volunteers, state agency employees, and researchers.

You don't need to know how to code. See [CONTRIBUTING.md](CONTRIBUTING.md) for simple, step-by-step instructions on how to submit a correction or add a new state's data.

## Repository Structure

```
state-data/
├── AK - Alaska/
├── AL - Alabama/
├── AR - Arkansas/
├── ...
├── IN - Indiana/
│   └── Indiana_cvso.csv    ← Example: CVSO directory, 92 counties
├── ...
└── WY - Wyoming/
```

## Links

- 🌐 [AVSOPS.com](https://avsops.com) — The live directory
- 📖 [Wiki](https://github.com/avsops/state-data/wiki) — Data format specs, contributing guide, state status
- 📋 [Project Board](https://github.com/users/avsops/projects/1) — State data collection progress
- 🤝 [CONTRIBUTING.md](CONTRIBUTING.md) — How to help

---

*AVSOPS is a free, nonpartisan, organization-agnostic directory. We represent every veteran service organization equally — from American Revolution-era patriotic societies to post-9/11 groups — across all 3,144+ U.S. counties.*
