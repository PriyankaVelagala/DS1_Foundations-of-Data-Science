# DS1: Analysis of World Happiness Report 
Quan Bui, Sarah Hadlow, Mahdia Khan, Priyanka Velagala, Yujin Yang

For full report, see: [Happiness Report - Analysis & Findings.pdf](https://github.com/PriyankaVelagala/DS1_Foundations-of-Data-Science/blob/main/Group%2029%20-Happiness%20Report%20-%20Analysis%20%26%20Findings.pdf)

# Overview 
Our dataset, the World Happiness report ranks countries based on their level of happiness. The report uses a survey conducted by the Gallup World Poll that asks a question, known as the Cantril ladder, where participants rank their own lives on a scale of 0 to 10, where the two extremes represent the worst and the best possible lives they can imagine for themselves, respectively. The report also provides a breakdown of the influence of the following six factors - Economy, Family, Health (Life Expectancy), Freedom, Government Trust (Corruption) and  Generosity and their contribution to the overall Happiness Score. 

# Dataset & Objective 
The six factors that contribute to the happiness score are factors that experts believe measure well-being and consequently the progress of a nation. Our primary objective was to determine whether the hypothesis that nations are in fact targeting policies, in regards to these six factors, to improve their nation’s well being  is true. This was tested by  conducting an year over year analysis of the happiness score and its contributing factors at the global, regional and national level from the years 2015 to 2019. 

With this approach, we were able to determine if the hypothesis holds true as if policies were being targeted to improve a nation’s well being in any of the six areas for a given year, this would be evident in the results of the Happiness scores from the subsequent year. 

# Data Quality 
The data quality across all years was fairly satisfactory with limited instances of missing values. As the survey gained recognition in recent years, more countries participated which meant some (< 10%) countries had missing value in earlier years. This was handled by excluding those countries from analysis for the missing years. Some other data quality issues we addressed before analysis were variations and changes in country names across each years’ dataset. This was handled by updating the country name from older years to use the value from the most recent dataset. The datasets also dropped the region field in the more recent years. However as we wanted to explore regional trends/differences, for data sets after 2017 (with missing region values), countries were updated to use the region identified for the same country in an earlier dataset.

# Analysis & Findings 
The analysis of the data revealed a complex picture. Overall, the average Happiness score across all countries increased slightly between 2015 to 2019, without significant changes in the regional scores. Bucking against the generally upward trendline, the average happiness score decreased in 2017.  

Between 2015 to 2019, the Health, Economy and Family factors increased, while the Freedom, Trust and Generosity factors either remained flat or decreased. Though these trends might reflect the absolute changes in these factors, they might also reflect the changes in relative contribution of these factors to the Happiness score. The causal relationships among these factors and the happiness score is difficult to conclude.

The Economy factor has a positive linear relationship with the happiness score, indicating that people in stronger economies are more likely to feel happier. Consequently, regions known for having strong economies have higher happiness scores, and regions with less robust economies have lower Happiness scores. A similar story is found in the Family factor, which shows that people and regions with good social support tend to feel happier than those without. The Health factor experiences the similar upwards trend. It is found that the East Asia region has the highest health score as a percentage contribution to the overall Happiness Score, and  the top ten countries in this aspect are regionally diverse.

For the Freedom factor, the same pattern is observed across regions: In 2016 almost every country experienced low levels of freedom which then gradually grew back to the same level in 2017 as we saw in 2015. There was an all-time high in 2018, falling in 2019 back to a similar level that we observed in 2015 and 2017. Meanwhile, the related Trust factor has been on a steady decline globally except for North America, where there was about a 7% decline in 2017, which eventually increased back up to 25% in 2019.

The Generosity factor indicates a positive direct relationship with happiness between 2015-2016, and a negative relationship from 2017 – 2019, which resulted in a net decrease between 2015 to 2019. The contribution of the generosity factor to the overall happiness score is the lowest among the factors, at most being 5 % for the examined period.

