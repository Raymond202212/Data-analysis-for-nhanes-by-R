# Data-analysis-for-nhanes-by-R
Assignment 1: Overall self-evaluated health strata, mental health, and sleeping condition of American adults: An analysis of NHANES dataset based on gender in 2011

Baseline Factors:
1. Most of the respondents are in middle aged
2. Most of the respondent are overweight / obese
3. A majority (> 50 %) of the respondent are white

Main Results:
1. 82% and 84% of the women and men reported themselves as at least “good general health”, while 53% and 65% of the women and men self-evaluated with no days of bad mental health.
2. Men tend to suffer less from depressive symptoms
3. Women tend to sleep longer than men
4. However, comparing to men, women are more susceptible to sleeping trouble. (OR = 1.57, 95%CI = (1.33, 1.87))

Conclusions:
1. Bad mental health and depressive symptoms tend to occur more on adult women comparing to men. 
2. Even though women tend to sleep longer than men, the occurrence of sleeping trouble in women is not to be undermined.




Assignment 3: Sleeping Hours: Do Demography and Habit Matters?
    
1. Result: With an average sleeping hour is 6.84 hours (standard deviation (SD)=1.33 hours), the sample included 1496 females (51.0%), and the average age was 47.93 years (SD=17.01 years). 1584 objects (54.0%) were married, 552 (18.8%) were not, and 278 (9.5%) were divorced. 1554 objects (53.0%) were physically active, 1647 (56.2%) and 564 (19.2%) were non-regular smokers and current active smokers, respectively. The median (1st quartile, 3rd quartile) of computer and TV usage time per day are 0.5 (0.5, 2) and 2 (1, 4) hours, respectively.
Apart from computer and TV usage hours per day, other predictors had statistically significant linear relationship with night sleeping hours (α=0.05). In the multiple regression model, age (age2: (β=7.363×10-4, 95% Coefficient Interval (CI): [5.573×10^-4, 9.152×10^-4]), age: (β=-0.069, 95% CI: [-0.087, -0.050]), indicating 47-year-olds are expected to sleep least), male (β=-0.116, 95% CI: [-213, -0.019]), some marital status (divorced: (β=-0.318, 95% CI: [-0.485, -0.150]), separated: (β=-0.502, 95% CI: [-0.799, -0.206]), widowed: (β=-0.368, 95% CI: [-0.580, -0.157]), compared to the status married), being physically active (0.113, 95% CI: [0.015, 0.212]), and some smoke status (smoke now: (β=-0.355, 95% CI: [-0.503, -0.206]), comparing to current non-smoke) statistically significantly predicted night sleeping hours, whereas computer (β=0.035, 95% CI: [-0.001, 0.070]) and TV usage hours (β=-0.005, 95% CI: [-0.125, 0.110]) were not. Despite the low adjusted R2 value (0.05), The overall regression was statistically significant (F(13, 2918) = 13.37, p<0.001). Additionally, the VIF test, Q-Q plot for residuals, and residual-fitted plot showed the model meets the assumptions (See supplemental file).

2. Conclusion: Age, gender, marital status (divorced, separated, widowed compared to married status), physically active status, and actively smoking influence night sleeping hours to a significant but limited extent, indicating that the impact factor for the sleeping hour is a vast and complex issue apart from the factors mentioned here.
