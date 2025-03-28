# OTA Pricing Analysis

This project analyzes the price of beach pool villas across three Online Travel Agencies (OTAs): Agoda, Traveloka, and Trip.com. The goal is to determine whether there is a significant difference in the average price per night for beach pool villas across the three OTAs.

## Problem Statement

As a traveler, you want to understand if there is a price difference for beach pool villas listed on different OTAs. By answering this question, you can better plan your travel budget. The villas in question must meet the following criteria:
- Beach pool villas in Thailand
- At least the following features: internet, karaoke room, swimming pool, and capacity for at least 6 persons.

### Deliverables

1. **Data Collection**
   - Randomly collect price data from three OTAs (Agoda, Traveloka, Trip.com) for beach pool villas in Thailand.
   - Ensure data is collected on the same day and within the same time window (no more than 1 hour apart) to minimize price fluctuations.
   - The dataset must include at least 30 samples for each OTA, recorded over the span of one month.
   - The data should be saved in an Excel file in the following format:


2. **Data Exploration (EDA)**
   - Use Python, R, or Excel to explore the data.
   - Plot histograms (with 5 bins) for each OTA's price distribution and report statistical parameters like mean and standard deviation.

3. **Normality Test**
   - Conduct a Chi-squared test (in Excel) and a Q-Q plot (in Python/R) to test the normality of the data.
   - Provide the p-value from the Chi-squared test and the Q-Q plot for interpretation.

4. **Analysis of Variance (ANOVA)**
   - Perform an ANOVA test in Excel to determine whether there is a significant difference in average prices between the three OTAs.
   - Provide the hypothesis, ANOVA test results, and interpretation of the p-value.

### Conclusion

Based on the Analysis of Variance (ANOVA), conducted to examine whether there is a significant difference in the average prices of beach pool villas across the three OTA platforms Agoda, Traveloka, and Trip.com, it was found that the P-value is 0.98318, which is greater than the significance level of 0.05. Furthermore, the F-value = 0.01696 is lower than the critical F-value = 3.08824. These results indicate that there is no statistically significant difference in the average prices among the three groups. At the 95% confidence level, we fail to reject the null hypothesis, which states that the OTA platforms do not influence the average prices of beach pool villas. This suggests that the observed price differences are likely due to random variation rather than being attributable to the specific platform used. However, this result may not be entirely reliable because the data does not follow a normal distribution, as indicated by the Q-Q plot and the Shapiro-Wilk test. ANOVA assumes that the data within each group is normally distributed. When the data deviates from normality, the results of ANOVA may become unreliable. Therefore, given the violation of the normality assumption, the ANOVA results could be unreliable. In this case, alternative methods should be considered to obtain more valid results.

