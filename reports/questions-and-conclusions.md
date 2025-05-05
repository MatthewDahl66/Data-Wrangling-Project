# Questions​

Do teams perform better when they heavily lean towards passing offense, rushing offense, or a mix
of the two (balanced approach) ​

Is there a penalty threshold where the effect on winning percentage sticks out?​

Do penalties committed in certain quarters or critical moments have a higher effect on a team's
chance to win?​

Does coaching play more of an impact than free agent spending?​

Does the amount of money spent in certain positions make more of an impact than others(QB vs.
K, etc.)?​

# Challenges​

Correlation between penalties and winning percentage in specific categories may be hard to prove
due to lack of records and/or other factors coming into play (opponent strength of schedule)​

Machine Learning​

Finding a direct correlation between team play style and team success​

# Research Question #1: How do teams that spend the most money in free agencies perform season to season?

We did a test to see if we can predict win/loss percentage, based off of contract money spent and this
was our result. ​

Mean Absolute Error (MAE): 0.17​

R² Score: -0.02​

Linear Regression Coefficients: [-0.01246599], For every unit increase in free agent spending, the
win/loss percentage is predicted to decrease by approximately 0.0125 (or 1.25%)​

Linear Regression Intercept: 0.4964814814814814, When a team spends no money on free agents, the
model predicts that the win/loss percentage would be approximately 49.65%​

Key Takeaways:​

- Poor Model Fit: The negative R² score suggests that the model is not useful for predicting win/loss
percentage based on free agent spending.​

- Weak Relationship: The coefficient is negative, but it is small (-0.0125), and given the low R² score,
this relationship might not be meaningful or statistically significant.​

- No Predictive Power: Given the results, free agent spending doesn't appear to have a strong predictive
power for team performance in terms of win/loss percentage​

# ​Research Question 2: Is there a correlation between penalties committed by a team and its overall winning percentage?

We performed a univariate analysis on the number of penalties and found the following data: Mean
Penalties: 101.49, Median Penalties: 102.0, Standard Deviation of Penalties: 16.15, Min Penalties: 55,
Max Penalties: 163.​

We then performed a bivariate test on penalties and win percentage to see if there was a correlation.
We found that the Pearson Correlation Coefficient between penalties and win percentage is -0.11. This
indicates a slight negative relationship, suggesting that teams with more penalties tend to have a lower
winning percentage.​

We then performed a hypothesis test and found that the P-value is 0.0036, so we reject the null
hypothesis. This means there is a statistically significant correlation between the number of penalties
and a team’s win percentage.

​

​
