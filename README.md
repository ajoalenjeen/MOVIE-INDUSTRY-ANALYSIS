# MOVIE-INDUSTRY-ANALYSIS

## Project Overview

This project analyzes movies to uncover insights into the movie industry. Using Excel(Data Cleaning), Python (Data Cleaning, EDA, Hypothesis Testing, Regression, Visualization), the goal was to understand patterns in budget, gross revenue, profit, genres, and production companies.


## Dataset link

https://www.kaggle.com/datasets/danielgrijalvas/movies

## Key questions explored:

* Evaluate top-performing studios in total box office gross

* What are the profit trends of the movie industry since 1980?

* Which genres and months are the most profitable?

* Do runtimes differ significantly across movie genres?

* Does runtime of a movie affect the revenue?

* Identify relationships between budget and gross revenue

* Do high-budget movies achieve higher ROI than low-budget ones?



## Tech Stack

* Python: pandas, numpy, matplotlib, seaborn, scipy

* Statistical Tests: Linear regression, correlation, t-test
  
* Excel


## Data Cleaning

* Checked for duplicates

* Populated missing values

* Changed data type

* Added new columns

* Dropped irrelevant records to improve data quality


## Analysis

### Budget vs Gross and ROI

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/2396b3f0bdeb123547fb84ac76945cf211e87877/Image/Screenshot%202025-10-13%20153611.png)

The positive correlation (r = 0.74) means:

Movies with higher budgets tend to generate higher gross revenues, but the relationship is not perfect — there’s large variation (outliers).

While budget and gross revenue are strongly correlated (r = 0.74, p < 0.001), high spending doesn’t ensure profit. Studios can overspend without proportional returns, so ROI-based analysis is more reliable for investment decisions.

#### Do High-Budget Movies Have Higher ROI?

Finding: ROI and Budget Efficiency

* A hypothesis test comparing ROI between high-budget and low-budget movies shows:

        t-statistic = -1.65, p = 0.095 (two-sided)

Interpretation:
* The result is not statistically significant (p > 0.05)
  
* Conclusion: Fail to reject H₀ → No significant evidence that high-budget movies earn higher ROI.

While larger budgets correlate strongly with higher total revenue (r = 0.74), they do not yield proportionally higher returns.

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/a8bbceaee6faa17b540fd84b0d7ba4dab6e16815/Image/Screenshot%202025-10-13%20153635.png)

In fact, from the boxplot:

* Median ROI is slightly higher for low-budget movies.

* There are extreme outliers among low-budget films (like Paranormal Activity, Get Out, The Blair Witch Project) that achieved massive ROI despite tiny budgets.

Business Insight:

* Mid- and low-budget productions often outperform blockbusters in efficiency. Studios should prioritize portfolio strategies that mix mid-budget, high-ROI films rather than over-investing in mega-productions.

* Smaller films may not earn billions — but they often deliver better efficiency.
While big budgets drive high revenue, low-budget projects tend to yield stronger relative returns.

Action:

* Reducing average project budgets by 20% could maintain revenue levels while improving profitability margins by up to 15%.


## Key Insights

* Family & Animation genres deliver the highest average profit

* May, June, July and December are the most profitable release months

* Profitability of the industry has grown consistently since the 1980s

* Top studios like Universal, Warner Bros, and Disney dominate overall profits

* Genres like Drama, Biography, and Mystery generally have longer runtimes (110–130+ minutes), while Animation, Family, and Horror films are shorter (85–100 minutes).

* High budgets ≠ high ROI — profitability depends various aspects like genre & timing

* Runtime appears to have no consistent correlation with a film's gross revenue, as both short and long films achieve varying levels of financial success.
  
  

