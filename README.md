# COPD & Asthma Interactive Dashboard — Patient & ICB Manager Views

Two interactive dashboards built for two very different audiences — a COPD
patient managing their day-to-day condition, and an Integrated Care Board (ICB)
manager overseeing respiratory care across a region — designed around real
user interviews and NHS/PHE data.

## Background

COPD affects an estimated 1.2 million people in the UK, making it the second
most common lung disease after asthma, and a major driver of hospital
admissions and GP workload. Monitoring its prevalence and quality of care
matters both for the people living with it and for the services managing it
at scale — which is why this project builds two dashboards for two very
different sets of needs, rather than one generic view.

## Data Sources


| Dataset | Details | Source |
|---|---|---|
| Quality Outcomes Framework (QOF) | GP practice level QOF 2020–22 for COPD and asthma | NHS Digital |
| General Practice (GP) Information | List of GP practices in the UK including postcode and CCG code | NHS Digital |
| GP Practice Physical Location | Longitude/latitude data for GP practices by postcode | Ordnance Survey |
| PHE indicators for COPD/asthma | CCG-level QOF indicator data | Public Health England (now UKHSA) |
| CCG to ICB mapping data | Data to link CCGs and ICBs | NHS Digital |


## Dashboard 1 — Patient View

**Designed for:** a 68-year-old female, COPD for 7 years, former smoker, with
seasonal flare-ups and an inhaler + smartwatch (activity & O₂ tracking) —
based on a real patient interview.

**Requirements gathered from interview:**
- COPD information and overview section
- Weather-related data to flag flare-up risk
- Interactive map of nearby GP practices
- Personalised deterioration risk calculator
- Medication schedule + reminders
- Smartwatch data sharing (activity & oxygen levels) with care team

**Design preferences:** colourful, user-friendly, simple/non-technical,
personalised, large text, uncluttered layout, line charts.

**Page 1 — COPD overview, "what's happening in the lungs," risk factors, and
patient self-management tips:**


**Page 2 — Interactive COPD/asthma deterioration risk calculator, with
symptom checklist and personalised risk level output:**


## Dashboard 2 — Manager View

**Designed for:** an ICB manager for respiratory disease, monitoring
population health outcomes and service delivery across GPs, hospitals, and
community teams, reporting to the ICS — based on a manager interview.

**Requirements gathered from interview:**
- Hospital admissions to assess primary care effectiveness
- GP performance data (QOF achievement, underperforming practices)
- Regional COPD/asthma prevalence
- Average interventions per COPD patient
- Interactive map by GP location/region
- Comparison graphs and heatmaps for GP performance
- Filters by indicator, geography, and demographic breakdown (age, gender,
  ethnicity) to surface inequalities

**Design preferences:** clear, simple, uncluttered (no images), comparative
bar charts, line charts for trends, maps for regional overview, strong
emphasis on interactivity and breakdowns.

**Page 1 — Regional admissions, COPD/asthma admission proportions by region,
and age-based asthma admission comparisons:**


**Page 2 — GP performance overview: best/worst performing GP practices by
achievement score, filterable by NHSE region and ICB:**

## Design Process

Both dashboards were built around structured interviews with a simulated
patient and manager persona to identify real information needs and
visualisation preferences, rather than assuming what each audience wants.
This shaped very different outcomes: the patient dashboard prioritises
warmth, simplicity, and personal relevance, while the manager dashboard
prioritises density, comparability, and drill-down filtering — reflecting
the different decisions each user needs to make.



## Tech Stack

Interactive BI dashboard tool Power BI built 
