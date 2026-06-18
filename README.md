# Medicine Dataset — Cleaning & Analysis

## Overview

This project covers end-to-end processing of a medicine dataset containing drug names,
therapeutic classes, use cases, substitutes, and side effects.

## Dataset

- **Source:** Raw medicine records
- **Cleaned file:** `medicine_cleaned.csv`
- **Records:** ~224,000 rows

| Column | Description |
|---|---|
| `name` | Medicine name |
| `habit_forming` | Whether the drug is habit-forming |
| `Therapeutic_Class` | Drug category (e.g. Anti Infectives, Respiratory, Cardiac) |
| `Use` | Medical condition treated |
| `substitutes` | Alternative medicines |
| `side_effects` | Known side effects |
| `num_side_effects` | Count of side effects |
| `hasSubstitutes` | Boolean — whether substitutes exist |

## Tools Used

- **Python** — data cleaning and preprocessing
- **Power BI** — interactive dashboard and insights
- **Excel** — intermediate data exploration

## Project Structure

```
├── medicine_cleaned.csv        # Cleaned dataset
├── cleaning.py                 # Python cleaning script
├── medicine_dashboard.pbix     # Power BI report
├── medicine_data.xlsx          # Excel workbook
└── README.md
```

## Key Insights (from Power BI)

- Distribution of medicines by therapeutic class
- Habit-forming vs non-habit-forming drugs
- Average number of side effects per class
- Substitute availability across drug categories
