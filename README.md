# EMEA Outreach Sequence Dashboard

Interactive single-file HTML dashboard for analysing SAP DG outreach campaign performance across EMEA Market Units and Lines of Business.

## What it shows

- **541 sequences** matched across 8 MU DG Plans + 4 LOB DG Plans
- Outreach engagement metrics: Reply Rate, Open Rate, Click Rate, Opt-Out Rate
- Curators coverage — campaigns supported by the DG Curators team
- Pipeline generated vs target (ACV kEUR)
- Top performing sequences by MU and by LOB with direct links to Outreach
- SDE-level breakdown

## How to use

Just open `EMEA Outreach Dashboard v2.html` in any browser. No server needed.

## Data sources connected

| File | Connected via |
|------|--------------|
| DG Action Plans (MU + LOB) | Sequence ID extracted from Sequence Link URL |
| Outreach Reports | Sequence ID → Sequence_Stats sheet |
| Curators MS List | WBS Code + MU (normalised) |
| Global Cloud Pipeline Analyzer | WBS Code = Opp Campaign ID |

## MU name normalisation

| Raw name in files | Dashboard name |
|---|---|
| CS Southern Europe (in files) | CS Spain |
| CS Spain (DG Plan file) | CS Spain |
| CS Türkiye / Israel / Portugal / Greece & Cyprus | CS Southern Europe |
| CS Nordic | CS Nordics |

## Metrics

- **Reply Rate** = Prospects Replied ÷ Prospects Total
- **Open Rate** = Prospects Opened ÷ Prospects Total
- **Click Rate** = Emails Clicks ÷ Emails Deliveries
- **High Performer** = Reply Rate ≥ 5% with ≥ 15 prospects
- **Pipeline Attainment** = Actual ACV kEUR ÷ Target kEUR

Built by DG Curators Team · Updated Jun 2026
