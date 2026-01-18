## Data Cleaning Summary

- Raw data source: data/raw/survey_responses_raw.xlsx
- Cleaning tool: Excel (Phase 1), SQL (Phase 2)

### Key Cleaning Steps
- Standardized employment types
- Converted hour ranges to numeric averages
- Normalized yes/no fields to binary
- Handled missing values using documented assumptions

### Assumptions
- "45+" hours treated as 45
- "<5" sleep treated as 5
- Free-text stress mapped to 1–5 scale
