# Edinburgh Road Traffic Accidents Analysis (2018)

This repository contains an analysis of road traffic accidents in Edinburgh during 2018. The data is sourced from the UK Government's open data platform, focusing on patterns in accident timing, severity, and circumstances.

## Dataset

- **Source:** UK Government Road Safety Data
- **Dataset name:** `accidents`
- **Key variables:**
  - Time of accident
  - Day of week
  - Severity level (Slight, Serious, Fatal)
  - Weather conditions
  - Light conditions
  - Road surface conditions

## Analysis Workflow

### 1. Data Examination
- Load and inspect accident records
- Review variables and data structure
- Handle missing values and data quality issues

### 2. Temporal Analysis
- Analyze accident patterns by time of day
- Compare weekday vs. weekend distributions
- Examine seasonal trends

### 3. Severity Assessment
- Study distribution of accident severity
- Identify factors correlated with serious/fatal accidents
- Analyze geographical patterns of severe incidents

## Visualization

Key visualizations include:
- Density plots comparing weekday/weekend accident timing
- Severity distribution across different times
- Weather condition impact analysis
- Light conditions correlation studies

## Key Insights

* Distinct bimodal pattern in weekday accidents (morning/evening commute peaks)
* More evenly distributed accidents on weekends
* Afternoon peaks more pronounced than morning peaks
* Slight accidents form the majority across all time periods
* Serious accidents maintain consistent proportion throughout the day
* Fatal accidents show no clear temporal pattern

## Requirements

* R (≥ 4.0)
* Packages: 
  - tidyverse (data wrangling and visualization)
  - dsbox (dataset)
  - knitr (document rendering)

## Repository Structure

```
.
├── hw-03-accidents.Rmd    # Main R Markdown document
├── hw-03-accidents.html   # Knitted output (rendered report)
├── README.md             # Project overview (this file)
└── img/                  # Supporting images
```

## Next Steps

* Analyze correlation with traffic volume data
* Study impact of road infrastructure changes
* Investigate relationships with public transport schedules
* Compare patterns with other UK cities
* Develop predictive models for high-risk periods

**Understanding traffic accident patterns is crucial for improving road safety and urban planning!**