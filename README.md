1. Data set Description:
The project relies on accuracy of data. The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The data-sets are made available to public for the purpose of health data analysis. The data-set related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. Among all categories of health-related factors only those critical factors were chosen which are more representative. It has been observed that in the past 15 years , there has been a huge development in health sector resulting in improvement of human mortality rates especially in the developing nations in comparison to the past 30 years. Therefore, in this project we have considered data from year 2000-2015 for 193 countries for further analysis. The individual data files have been merged together into a single data-set. On initial visual inspection of the data showed some missing values. As the data-sets were from WHO, we found no evident errors. Missing data was handled in R software by using Missmap command. The result indicated that most of the missing data was for population, Hepatitis B and GDP. The missing data were from less known countries like Vanuatu, Tonga, Togo, Cabo Verde etc. Finding all data for these countries was difficult and hence, it was decided that we exclude these countries from the final model data-set. The final merged file(final dataset) consists of 22 Columns and 2938 rows which meant 20 predicting variables. All predicting variables was then divided into several broad categories:​Immunization related factors, Mortality factors, Economical factors and Social factors.

2. Key findings 

The life expectancy dataset had 22 variables and 2,938 observations. No duplicates were found, but missing values occurred in variables like Hepatitis B, GDP, and population over 15. Outliers in population were addressed using the median. China, India, and the US had the largest populations; Japan had the smallest among the top ten. Fertility rates declined more slowly in Nigeria and Pakistan. Correlation results revealed that life expectancy was positively correlated with schooling (r = 0.63) and negatively with fertility rate (r = −0.64), both statistically significant (p < 0.05). Multiple regression identified several significant predictors:
• Developing country status: β = −1.13, p < 0.05
• Adult mortality: β = −21.35, p < 0.05
• Income composition: β = 22.33, p < 0.05
• Measles cases: β = 1.75, p < 0.05
• Polio immunization: β = 6.23, p < 0.05
• Total expenditure: β = 9.17, p < 0.05
• Schooling: β = 2.18, p < 0.05
Regional analysis in 2015 showed Europe led with an average of 79 years, followed by
the Americas, with Africa lowest at 65.2. Within Africa, SADC (65.5 years) had higher
life expectancy than EAC (61.4 years).

3. Discussion of the Findings
This study confirmed that life expectancy is driven by intertwined social, economic, and health-related factors. High adult mortality rates remain a major barrier, especially in
low-income regions. Education and income were found to be strong positive predictors, suggesting that investment in human capital directly impacts longevity.
Notably, developing country status was associated with lower life expectancy despite potential medical advancements, indicating persistent systemic disparities. Immunization coverage and healthcare spending also positively impacted longevity, highlighting the importance of preventive care. Regional disparities remained stark, with Africa lagging significantly. Within Africa, the gap between SADC and EAC emphasizes the role of regional policies and infrastructure in health outcomes. The study supports the call for integrated, multi-sectoral efforts to address these gaps.

4. Conclusion

Life expectancy is a critical metric for assessing population well-being. This study highlights that longevity is influenced by adult mortality, economic resources, education, and healthcare investments. Despite global improvements, inequalities persist. Comprehensive policy approaches focusing on education, income equity, healthcare access, and data quality are essential to improving global life expectancy outcomes.
