# Carbon Emissions: A Deep Dive into Global, Nordic, and IKEA Trends

## Overview

This project provides an in-depth analysis of global carbon emissions, focusing on key regions like the United States, China, Russia, and Europe, as well as the Nordic countries, and a case study on IKEA's sustainability efforts. It combines various data sources and analytical methods to understand emission trends, compare per capita emissions, and assess the effectiveness of emission reduction strategies.

## Key Features

- **Global Emissions Analysis**: Visualizes and analyzes total and per capita carbon emissions across major global emitters, providing insights into disparities between total emissions and per capita contributions.
- **Nordic Countries Analysis**: Examines the emission reduction strategies and energy mixes of Sweden, Norway, Denmark, and Finland, showcasing their significant progress in reducing reliance on fossil fuels.
- **IKEA Case Study**: Provides a detailed examination of IKEA's sustainability reports (2019-2023), highlighting the challenges of changing baseline data, evaluating IKEA's material and logistics-related strategies, and reflecting on their overall emission reduction efforts.

## Methodology

- **Data Visualization**: Utilized geographic mapping, line graphs, linear regression, three-year rolling averages, five-year averages, Sankey diagrams, and other visual tools to represent emission data trends.
- **Statistical Approaches**: Applied linear regression, five-year averages, and three-year rolling averages to analyze emission trends amidst changing baseline data.
- **Case Study Analysis**: Examined IKEA's efforts in key categories like material production, product manufacturing, product use at home, and transportation, focusing on challenges related to transparency and sustainability.

## Data Sources

- **CO2 Emissions Dataset**: Publicly available on Kaggle ([link to dataset](https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022)). This dataset includes total emissions, sector-wise emissions (coal, oil, gas, etc.), and per capita metrics for a comprehensive understanding of global trends.
- **IKEA Annual Sustainability Reports (2019-2023)**: IKEA's sustainability initiatives and emission reduction data were extracted from their annual reports.

## Findings

- **Global Trends**: The U.S., China, and Russia contribute significantly to global emissions, but analyzing per capita emissions offers a more equitable perspective on individual countries' impacts.
- **Nordic Countries**: Strong environmental policies, renewable energy adoption, and carbon taxes have helped these countries make substantial progress in reducing emissions.
- **Corporate Case Study (IKEA)**: Reveals inconsistencies in reporting due to frequent baseline adjustments. Despite various sustainability initiatives, there are still upward trends in some emission categories, underlining the need for standardized reporting methodologies.

## Visualizations

- **Global and Regional Emissions Maps**: Created using geographic visualizations to easily identify key emitting countries.
- **Emissions Trends**: Line plots, scatter plots, Sankey diagrams, linear regression lines, three-year rolling averages, and other visual tools were used to illustrate emissions by country, region, and IKEA’s internal emission categories.

## Insights for Future Action

The analysis points to the need for:

- **Standardized Carbon Accounting**: More scientifically grounded and replicable methods are essential for accurate comparisons and transparency.
- **Corporate Strategies for Improvement**: Companies like IKEA should focus on standardizing their reporting processes and addressing areas with increasing emissions, while also maintaining successful sustainability efforts.
- **Policy Leadership**: Effective and robust regional policies are essential to encourage emission reduction globally, highlighting the importance of cooperative action between nations and the value of strong legislative frameworks.

## How to Use This Repository

- **Data and Scripts**: The repository contains the CO2 emissions dataset, scripts for visualizing emissions trends, and R Markdown files for generating the report.
- **Reproducibility**: To replicate the analysis, simply open the R Markdown files and execute the code chunks sequentially.

## Installation and Requirements

- **R and RStudio**: Install version 4.4.1 of R and the latest version of RStudio.
- **Packages**: Use the following command to install the required packages:
  ```r
  install.packages(c("tidyverse", "ggplot2", "sf", "rnaturalearth", "rnaturalearthdata", "RColorBrewer", "knitr", "kableExtra", "patchwork", "ggalluvial", "zoo"))
  ```
- **Running the Analysis**: Open `Carbon_Emissions_Analysis.Rmd` in RStudio and knit the file to generate the report.

## License

This project is licensed under the MIT License.

## Acknowledgments

- **Data Source**: Kaggle CO2 Emissions Dataset, IKEA Annual Sustainability Reports (2019-2023)
