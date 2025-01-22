# Factors Influencing World Hunger

## Project Overview

This project explores the critical issue of world hunger by examining the factors influencing hunger challenges globally. Hunger, as defined by the United Nations Hunger Report, refers to severe food insecurity and undernourishment. Using multiple datasets on hunger, climate, economy, agriculture, and malnutrition, the project identifies patterns, trends, and correlations that shed light on the persistent global challenge of hunger. In addition to addressing these real-world issues, the project aimed to enhance skills in SQL for querying and analyzing data, visualizing complex relationships, and working with databases to uncover meaningful insights. The goal was to explore these datasets and understand the influence each factor has on world hunger while developing technical proficiency in data analysis. Click [here](https://github.com/TasheikaW/Hunger-Influences/blob/26a636ca51440bc2235add6bfc066783fffe1dce/Factors%20Influening%20Global%20Hunger.ipynb) to see the full project.

## Data Sources

- Global Hunger Index Dataset: Measures hunger levels in various countries across four years (2000, 2006, 2012, and 2021).
  Published by Concern Worldwide and Welthungerhilfe, processed by Our World in Data.
- Economic Indicators Dataset: Includes GDP, trade balance, per capita GNI, and household consumption expenditure.
Source: Kaggle (Creative Commons Public Domain).

- Climate Dataset: Tracks CO2 emissions, rainfall patterns, and global temperature changes (2000–2024).
Source: Kaggle (Community Data License Agreement).

- Agriculture Dataset: Provides data on crop production, fertilizers, and land use (2000, 2006, 2012, 2021).
Source: Food and Agriculture Organization (FAO).
- Malnutrition Dataset: Focuses on mortality rates linked to malnutrition globally.

## Tools

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- SQL 
- Data visualization libraries for exploration and analysis

## Data Cleaning

- Addressed null values and dropped irrelevant columns (e.g., "Year Code").
- Standardized variable names for consistency across datasets.

## Guiding Questions

1. How have hunger levels changed over time in different countries, and which countries show improvements or declines?
2. What regions have been most affected in our climate data and has this possibly impacted global hunger and malnutrition deaths?
3. How have changes in agricultural produce impacted global hunger in regions with the highest global hunger index score?


## Data Analysis and Results

This section outlines key analyses performed to uncover the factors influencing world hunger using five datasets: Global Hunger Index, Economic Indicators, Climate, Agriculture, and Malnutrition.

#### Key Findings:
A global decline in hunger scores was observed, indicating progress in reducing hunger.

<img width="691" alt="Image" src="https://github.com/user-attachments/assets/af0470c6-6cbe-4bce-880a-ed7bc0bbc127" />
<img width="694" alt="Image" src="https://github.com/user-attachments/assets/f54835e3-08d0-4c0d-a9b7-d51c8bda475e" />

The line plot shows declining Global Hunger Index (GHI) trends from 2000 to 2020 for most low-GDP countries, indicating progress in reducing hunger. Somalia experienced a spike in GHI in 2012 due to severe drought, agricultural disruption, and conflict, while Malawi, Ethiopia, and Liberia showed steady improvements, with Malawi and Ethiopia making the most significant progress.

What Economic Factors might be affecting these changes in Hunger Levels?

<img width="656" alt="Image" src="https://github.com/user-attachments/assets/048140b4-4796-4128-b8c6-45ee707abd4c" />

The heatmap shows correlations between the Global Hunger Index (GHI) and economic indicators like GDP per capita, GNI per capita, trade balance, and per capita consumption. GHI has a moderate negative correlation with GDP and GNI, indicating that as national wealth increases, hunger decreases. Per capita consumption shows the strongest negative correlation, highlighting that higher household purchasing power directly reduces hunger by improving food access. Trade balance has a weak negative correlation, suggesting minimal direct impact on hunger. Overall, the analysis underscores that economic prosperity, household consumption, and income levels significantly influence hunger reduction, while trade balance plays a less direct role.

<img width="695" alt="Image" src="https://github.com/user-attachments/assets/ec7dde19-9356-4737-962a-5f865a628d3d" />

The bubble chart visualizes the relationship between average CO2 emissions (X-axis), average Global Hunger Index (GHI) scores (Y-axis), and the frequency of extreme weather events (bubble size and color). Countries like South Africa, Indonesia, and India show high GHI scores, CO2 emissions, and extreme weather events, while Brazil and China have high CO2 emissions but low GHI scores. A correlation matrix reveals moderate positive correlations between extreme weather events and GHI, as well as between CO2 emissions and GHI. These findings suggest that extreme weather events significantly disrupt food supply and elevate hunger levels, while CO2 emissions, linked to industrial activities, indirectly affect food security in high-emission countries.


#### Conclusion
This analysis explored the multifaceted factors influencing global hunger, focusing on economic indicators, climate conditions, and agricultural production. The findings highlighted a general decline in Global Hunger Index (GHI) scores over time, especially in lower-GDP countries, while nations like Somalia experienced setbacks due to severe drought and conflict, emphasizing the role of socio-political stability and climate. Economic prosperity, measured by GDP per capita, GNI per capita, and household consumption, showed strong negative correlations with hunger, underscoring the importance of internal wealth in addressing food insecurity.  

Climate factors, particularly extreme weather events and CO2 emissions, moderately correlated with higher hunger levels, disrupting food production in countries like South Africa, India, and Indonesia. In contrast, trade balance and sea level rise showed minimal direct impacts on hunger. Agricultural output correlated negatively with hunger levels, though its impact was constrained by factors like infrastructure, distribution, and political stability.  

This project underscores the complex interplay of economic, environmental, and social factors in addressing food insecurity, highlighting the need for integrated approaches and further research to identify effective solutions.

#### Limitations of the Analysis

- Data Availability: Incomplete or outdated data for some regions may skew results.
- Correlation vs. Causation: The analysis identifies correlations but does not confirm causative relationships.
- Simplification of Complex Issues: Hunger’s multifaceted causes, like political and social factors, may be oversimplified.
- Climate Data Gaps: Localized impacts of climate change, such as regional agricultural disruptions, are not fully captured.
- Interaction Effects: Limited exploration of how factors like economic growth and climate conditions interact.
- Timeframe Constraints: Analysis focuses on 2000–2020, potentially missing long-term trends and impacts.
- Data Quality: Variability in the accuracy and reliability of data sources may affect results.
- Policy and Governance Exclusion: Limited consideration of the role of policies, governance, and conflict resolution in hunger mitigation.

#### References
Global Food & Agriculture Statistics. (2017, November 16). Kaggle. https://www.kaggle.com/datasets/unitednations/global-food-agriculture-statistics?select=fao_data_forest_data.csv

Growmodo. (2024, October 9). Ethanol and Biofuel: What It Is and How It's Used. Nebraska Corn Board. https://nebraskacorn.gov/corn-101/corn-uses/ethanol/

Otekunrin, O. A. (2024). Assessing the prevalence and severity of global hunger and food insecurity: recent dynamics and Sub-Saharan Africa’s burden. Sustainability, 16(12), 4877. https://doi.org/10.3390/su16124877

Dickinson, D. (2024, August 26). What is sea level rise and why does it matter to our future? UN News. https://news.un.org/en/story/2024/08/1153596

“Data Page: Deaths from malnutrition”, part of the following publication: Esteban Ortiz-Ospina and Max Roser (2016) - “Global Health”. Data adapted from World Health Organization. https://ourworldindata.org/grapher/deaths-from-malnutrition-ghe

Owen, J. (2022, July 21). World hunger: Facts & how to help. Worldvision.ca. https://www.worldvision.ca/stories/food/world-hunger-facts-how-to-help

Our World in Data. (February 24, 2022). Global Hunger Index, 2000 to 2021. https://ourworldindata.org/grapher/global-hunger-index?tab=table&time=earliest..2021

Prasad Patil. Global Economy Indicators. (n.d.). Kaggle. https://www.kaggle.com/datasets/prasad22/global-economy-indicators

Bhadra Mohit. (2021). Climate change dataset. Kaggle. https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset

Balance of Trade and Balance of Payments. (n.d.). Econlib. https://www.econlib.org/library/Topics/HighSchool/BalanceofTradeandBalanceofPayments.html

Somalia famine worst in past 25 years | LSHTM. (n.d.). Www.lshtm.ac.uk. https://www.lshtm.ac.uk/newsevents/news/2013/somalia_famine.html

Nations, U. (2023). Glossary - amaWebClient. Un.org. https://unstats.un.org/unsd/snaama/Metadata/Glossary#





