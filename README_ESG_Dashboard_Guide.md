# ESG Intelligence Dashboard Guide

## Overview
This package includes a master Excel template, a structured JSON data file, and a usage guide for maintaining the ESG dashboard ecosystem.

## Included files
- ESG_Intelligence_Master_Template.xlsx
- esg_dashboard_data_master.json
- README_ESG_Dashboard_Guide.docx

## How the Excel template is organized
### Overview
Contains workbook navigation and a quick performance snapshot.

### Company_Info
Capture organization profile, reporting period, employee count, revenue, and ESG contact fields.

### Environmental_Data
Update emissions, energy, water, waste, and biodiversity metrics using current, previous year, and target values.

### Social_Data
Update workforce, safety, community, human rights, and product responsibility indicators.

### Governance_Data
Update board, ethics, risk, and stakeholder engagement metrics.

### Targets
Track key ESG targets, deadlines, owners, and implementation status.

### Benchmarks
Maintain industry comparison values by sector.

### Risks
Record ESG risk factors, scores, and mitigation actions.

### Dashboard_KPIs
Review summary indicators and formula-driven fields such as average pillar score, benchmark gap, and high-risk count.

## How to use the data file
The JSON file mirrors the dashboard structure and can be used directly by the HTML dashboard or other analytics workflows. Update it only after validating final values in the Excel workbook.

## Recommended workflow
1. Populate company and metric sheets.
2. Review target, benchmark, and risk data.
3. Validate KPI outputs.
4. Export validated values into the JSON file.
5. Refresh the dashboard.

## Good governance practices
- Update the package on a fixed reporting cycle.
- Maintain a source trail for each material metric.
- Lock formula cells before team-wide sharing.
- Use consistent units across reporting periods.
