# Low Insulin Diet Study

## Overview
This project analyzes the effects of four diet types—Keto, Low-Carb, Standard, and Control—alongside the use of Ozempic on weight loss, HOMA-IR, and fasting insulin levels over a 12-week study period with 50 participants. The analysis includes data cleaning, statistical analysis, and interactive visualizations to assess the impact of diet and medication on health outcomes. The data spans from January to April 2025 (with the report finalized on April 21, 2025).

## Tools and Technologies
- **R**: Used for data cleaning, statistical analysis, and generating visualizations.
- **Google BigQuery**: Used for initial data cleaning and querying.
- **Tableau Public**: Created interactive visualizations to display the findings.
- **R Markdown**: Generated a comprehensive HTML report with code, tables, and embedded plots.

## Project Files
- `low_insulin_diet_bigquery_cleaned.csv`: Cleaned dataset containing participant data (weight, HOMA-IR, fasting insulin) across 12 weeks.
- `Low_Insulin_Diet_Study_Report.Rmd`: R Markdown source file for the analysis report.
- `Low_Insulin_Diet_Study_Report.html`: Knitted HTML report with the full analysis, including code, tables, and a bar chart.
- `weight_over_time.png`: R-generated chart showing weight changes over the 12 weeks.
- `weight_loss_bar.png`: R-generated bar chart comparing average weight loss by diet type and Ozempic use.

## Visualizations
Check out the interactive visualizations on Tableau Public:  
[Low Insulin Diet Study Visualizations](https://public.tableau.com/app/profile/alexander.gallagher/viz/LowInsulinDietStudyVisualizations/DietStudyVisualizations)

## Findings
- **Keto and Low-Carb Diets**: Demonstrated greater weight loss and reductions in HOMA-IR and fasting insulin compared to Standard and Control diets.
- **Ozempic Impact**: Enhanced weight loss and metabolic improvements, particularly for participants on the Keto diet.
- **Control Group**: Showed minimal changes in weight and metabolic markers, as expected.

## How to Run
1. Clone this repository: `git clone https://github.com/AlexanderGS0x/Low-Insulin-Diet-Study.git`.
2. Install R and required libraries (e.g., `tidyverse`, `broom`, `knitr`).
3. Open `Low_Insulin_Diet_Study_Report.Rmd` in RStudio.
4. Ensure the dataset (`low_insulin_diet_bigquery_cleaned.csv`) and chart files (`weight_over_time.png`, `weight_loss_bar.png`) are in the same directory.
5. Knit the R Markdown file to HTML to reproduce the report.
6. View the Tableau visualizations via the provided link.

## Contact
For questions or collaboration, connect with me on [LinkedIn](https://www.linkedin.com/in/alexander-gallagher).
