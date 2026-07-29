# U.S. Healthcare Analytics Dashboard

A Power BI case study exploring U.S. healthcare operations and financial activity for 2019–2020.

The report connects patient, hospital, physician, payer, diagnosis, procedure, and transaction data in a dimensional model. It uses Power Query and DAX to surface operational and financial patterns across several dashboard views.

![Dashboard overview](assets/overview.jpg)

## Dashboard views

- Executive overview — high-level activity and performance indicators
- Hospital insights — utilization and hospital-level comparisons
- Patient outcomes — demographic and outcome patterns
- Provider metrics — physician, specialty, and payer relationships
- Monthly expenses — financial trends over time

## Skills demonstrated

- Data cleaning and transformation with Power Query
- Star-schema modeling with dimension and fact tables
- DAX measures and KPI design
- Interactive filtering and drill-down analysis
- Dashboard layout and stakeholder-oriented reporting

## Repository guide

| Path | Contents |
| --- | --- |
| `powerBI/US_Healthcare_Dynamics.pbix` | Main Power BI report |
| `data/` | Source tables, workbook, data dictionaries, and a working PBIX file |
| `assets/` | Dashboard screenshots and the entity-relationship diagram |
| `docs/` | Project synopsis and exported analysis |
| `notes/` | Supporting design, modeling, transformation, and DAX notes |

## Preview

| Executive overview | Hospital insights |
| --- | --- |
| ![Executive overview](assets/executive_summary.jpg) | ![Hospital insights](assets/hospital_insights.jpg) |

| Patient outcomes | Provider metrics |
| --- | --- |
| ![Patient outcomes](assets/patient_outcome_analysis.jpg) | ![Provider metrics](assets/healthcare_provider_metrics.jpg) |

## Explore the report

1. Clone or download the repository.
2. Open `powerBI/US_Healthcare_Dynamics.pbix` in Power BI Desktop.
3. Use the report filters to explore hospitals, patients, providers, payers, and time periods.

## Limitations

This is a portfolio analysis of historical sample data. It is not clinical guidance, a validated quality-measure system, or a substitute for current operational reporting.

