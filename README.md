# Indonesia Weapon Systems Database

**Live site → [defensedatabase.lab45.id](https://defensedatabase.lab45.id)**

An open-source OSINT reference tool tracking TNI (Tentara Nasional Indonesia) weapon systems, procurement timelines, supply chains, and strategic posture across all three service branches and Korps Marinir.

Maintained by **[LAB45 — Laboratorium Indonesia 2045](https://www.lab45.id)**.

---

## What it tracks

- **127 weapon systems** across TNI AU, TNI AD, TNI AL, and Korps Marinir
- Procurement status, contract values, delivery timelines, and supplier nations
- Progress against the Perisai Trisula Nusantara (PTN) modernization program and Minimum Essential Force (MEF) baselines
- Component-level supply chain analysis and dependency risk ratings for 14 major incoming platforms
- Strategic base deployment map with ALKI/EEZ overlays and a Deployment Simulation planner
- 24 strategic resource extraction sites assessed for airborne and amphibious vulnerability

## Tabs

| Tab | What's inside |
|-----|--------------|
| **Strategic Planning** | PTN progress bars vs. MEF 2024 baseline across all three shields |
| **Inventory** | Full searchable database with status, origin, base, and procurement source |
| **Country of Origin** | Sankey diagram, bar chart, supply chain explorer, and supplier network by contract value |
| **Base Map** | Current Deployment (ALKI/EEZ overlays) and Deployment Simulation (flashpoints, mining sites, range rings) |
| **Procurement Timeline** | Visual timeline by technology tier and administrative era (Soekarno → Prabowo) |
| **About** | Methodology, data sources, evidentiary standards, and supply chain dependency risk framework |

## Data standards

Inclusion requires **official MoD confirmation, a signed contract, or a verified IISS/SIPRI record**. Framework agreements, LOIs, and unverified media reports are not included.

Primary sources:
- IISS Military Balance 2025/2026
- SIPRI Arms Transfers Database
- Indonesian MoD / TNI official statements
- Evan Laksmana, IISS (Feb–Mar 2026)
- Asian Military Review, Indonesia Defense, Alert 5

## Architecture

Single-file React application (`index.html`) — compiled JS with D3 v7, deployed via GitHub Pages. No build step, no backend, no dependencies to install.

To run locally: download `index.html` and open it in any modern browser.

## Citation

If you use this database in research, journalism, or policy work, please cite:

> LAB45 (Laboratorium Indonesia 2045). *Indonesia Weapon Systems Database*. https://defensedatabase.lab45.id. Accessed [date].

## License

- **Code** — [MIT License](LICENSE)
- **Data & Analysis** — [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

You are free to share, adapt, and build on this work for any purpose, provided you give appropriate credit to LAB45 (Laboratorium Indonesia 2045) and indicate if changes were made.

## Contributing

Data corrections, updated contract values, and new system entries are welcome via GitHub Issues. Please cite your source when submitting a correction.

---

*This database is an independent analytical product. It does not represent the official position of the Indonesian government, TNI, or Kemhan.*
