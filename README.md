# Migration Dynamics in Latvia (2016-2025)

Public discussions around population movements often focus solely on gross arrival or departure numbers. The objective of this project is to analyze official Latvian migration statistics from 2016 to 2025 to determine the true demographic net impact on the country.

## Business Questions

1. Is net migration positive or negative overall across the given time period?
2. Which age groups drive brain drain?
3. How have migration flows changed across given country groups over time?
4. Are there noticeable differences in migration volumes and net gaps between men and women?

## Data Sources

Data is retrieved from [Oficiālās statistikas portāls](https://stat.gov.lv/lv). Two datasets are used, located under `data/raw` folder: `migration_by_region_group_2016_2025_raw.csv` and `migration_by_age_group_and_gender_2016_2025_raw.csv`.
The first dataset details immigration and emigration volumes, categorized by foreign country groups. The second dataset contains immigration and emigration counts broken down by age groups and gender.

## Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn
- **Visualizations**: Power BI Desktop
- **Environment**: Jupyter Notebook

## Methodology

1. **Data Cleaning**: Melting wide-format multi-header tables into clean long-format datasets, standardizing column names and data types, handling missing values and preserving Latvian character encoding.
2. **Transformation**: Calculating net migration in both datasets.
3. **Exploratory Data Analysis**: Identifying historical trends, anomalous spikes, and gender and age imbalances across years.
4. **Data Visualization**: Building interactive Power BI dashboard to present key findings visually.

## Key Findings

_This section will be populated with key metrics and visualizations upon completion of the analysis_.
