# KENYA LITERACY AND EDUCATION SURVEY DATA

## NON-TECHNICAL

1. **PRESENTATON:[Link](https://docs.google.com/presentation/d/1tYfeW8hYOm2mpPfyo3h6oIN3X4M98GGTel7d9TJihLo/edit?usp=sharing)**
2. **TABLEAU:[LINK](https://public.tableau.com/app/profile/ian.moire/viz/KenyaNationalLiteracyTrends/KenyaNationalLiteracyTrends)**


## Background
Literacy is a foundational component of human development and a key indicator of national progress. In Kenya, literacy levels influence access to education, employment, and healthcare outcomes. This dataset compiles national survey data from DHS and MIS programs between 2003 and 2022, offering a view of literacy across gender, age groups, and survey types.

## Objectives
1. To analyze literacy trends in Kenya over time using nationally representative survey data.
2. To compare literacy and education indicators across gender and demographic subgroups.
3. To identify gaps and disparities that can inform policy interventions.

## Research Questions
1. What are the gender disparities in literacy and education access?
2. How have literacy rates in Kenya evolved from 2003 to 2022?
3. Which indicators show the most significant improvement or decline?
4. How do sample sizes and survey types affect reported literacy outcomes?

## Dataset Description
The dataset used in this analysis is the literacy_national `Data.Humdata.org`. It contains 29 records with features such as 'SurveyId','IndicatorId','IndicatorOrder','IsTotal','IsPreferred','SurveyType','DenominatorWeighted',and 'DenominatorUnweighted'. Missing values, duplicates, and outliers were addressed as Feature engineering metrics, like ratios and percentages features were added to the dataset.

## Methodology
The analysis involves the following:
1. **Data Cleaning:** Handled missing values and outliers, and standardized indicator labels.
2. **Exploratory Analysis:** Identified key trends by creating visualization distributions such as histograms, bar graphs, and scatterplot.
3. **Feature Engineering:** Created calculated fields such as ratios and percentage features.
## Significance
This analysis provides a data-driven foundation for understanding literacy dynamics in Kenya. It highlights areas of progress, especially in gender equity and education access. The findings can support policymakers, educators, and development partners in designing targeted interventions that promote literacy growth.

5. **Visualization:** Used Tableau to build dashboards including line charts, bar charts, scatterplots, and heatmaps.

## Significance
This analysis provides a data-driven foundation for understanding literacy dynamics in Kenya. It highlights areas of progress, especially in gender equity and education access. The findings can support policymakers, educators, and development partners in designing targeted interventions that promote literacy growth.
## Conclusion
This analysis reveals steady progress in literacy rates, with disparities across gender and education levels. By leveraging DHS and MIS survey data, a Tableau dashboard has been built to visualize trends, gaps, and performance. The findings offer a data-driven foundation for educational planning.

## Summary of Key Findings
1. There are gender disparities, with women consistently reporting lower literacy and education levels than men.
2. Literacy rates have improved across both genders, especially in younger age groups.
3. Survey sample sizes vary, influencing the reliability of certain indicators.
4. Education access (secondary) remains limited, especially for women.

## Implications
Targeted literacy programs for women and regions are essential, as future surveys should ensure consistent sample sizes. The dashboard can be used to monitor the impact of literacy interventions over time. Insights can support funding decisions for education initiatives.

## Limitations
The dataset lacks regional, rural, and county-level granularity. Some indicators may be similar, requiring careful grouping. Variations in sample size may affect trend interpretation.

## Future Work
Incorporate rural, regional, and county-level data for insights. Connect literacy indicators to employment and health metrics. Use machine learning to forecast literacy trends or identify high-risk groups. 
## Reference
# ***data.Humdata.org***

**(https://data.humdata.org/dataset/dhs-data-for-kenya?force_layout=desktop)**
