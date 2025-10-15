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

### Average Profit of Movie Industry since 1980

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/c1e75624db99371f11aa5a1135b542ef2559bd18/Image/Screenshot%202025-10-15%20143048.png)

* 1980s–early 1990s: Profits relatively low and stable (average ~$20–40M).

* Mid-1990s onward: Gradual increase — growth of blockbuster era (CGI, franchises, global distribution).

* 2000s: Rapid climb — rise of major studios’ tentpole strategy (e.g., Harry Potter, Marvel, Lord of the Rings).

* 2010s–2020: Sharp surge — dominance of streaming-age mega franchises, higher budgets, larger global markets.

Average film profits have grown nearly 8× since 1980, driven by globalization, blockbuster franchises, and higher production budgets.
However, this growth is largely nominal — studios spend far more per film today, resulting in higher profits but not necessarily higher efficiency (as seen in the earlier ROI analysis).

### Average Profit per month

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/849956c022041ab4419ebb7d1a941ebbad56d7bb/Image/Screenshot%202025-10-15%20143211.png)

Finding: Seasonal Profit Trends

* Average profit peaks in May–July and November–December, aligning with global blockbuster and holiday release seasons.

* Summer releases generate the highest profitability (avg. $110M+), followed by holiday films (avg. $100M+).

* Autumn months (Aug–Oct) see the lowest returns.

Business Implications:

* Studios should schedule high-budget, family-friendly, or franchise films in summer and winter windows to maximize returns.

* Low-competition months (Sept–Oct) are best suited for niche or experimental releases, minimizing risk and maximizing audience share.

### Average profit per Genre

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/d375f5703b1d6842b895d2a70386935c64cceeec/Image/Screenshot%202025-10-15%20143236.png)

Finding: Profitability by Genre

* Family and Animation movies have the highest average profits (~$450M and $200M respectively).

* Action and Adventure follow, driven by global franchise performance.

* Horror and Mystery achieve strong returns relative to cost, though with lower absolute profits.

* Romance and Westerns are least profitable.

### Average Runtime per Genre

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/1187f878a39ba8ae79be4bd98d1a531b54514234/Image/Screenshot%202025-10-15%20143250.png)

Finding: Runtime Patterns by Genre

* Median runtime varies widely by genre.

* Dramas, Biographies, and Mysteries average ~120–130 minutes.

* Comedies, Horrors, and Animations cluster around 90–100 minutes.

* Action and Adventure films sit in the middle (~110–120 minutes).

Interpretation:

* Narrative-heavy genres naturally demand longer runtimes, while lighter or family-oriented genres optimize for audience turnover.

### Duration vs Gross

![image alt](https://github.com/ajoalenjeen/MOVIE-INDUSTRY-ANALYSIS/blob/0343a8cf7cc8380ea588e9557a3c9c20bbff4e8a/Image/Screenshot%202025-10-15%20143310.png)

An r = 0.28 means runtime explains only a small portion of a movie’s revenue.
In business terms:

* Longer movies slightly tend to make more money, but the effect is weak — other factors (genre, budget, marketing, release strategy) matter much more.

* While longer films may allow for more complex storytelling and perceived value, duration alone is not a strong predictor of commercial success.”

## Key Insights

* Family & Animation genres deliver the highest average profit

* May, June, July and December are the most profitable release months

* Profitability of the industry has grown consistently since the 1980s

* Top studios like Universal, Warner Bros, and Disney dominate overall profits

* Genres like Drama, Biography, and Mystery generally have longer runtimes (110–130+ minutes), while Animation, Family, and Horror films are shorter (85–100 minutes).

* High budgets ≠ high ROI — profitability depends various aspects like genre & timing

* Runtime appears to have no consistent correlation with a film's gross revenue, as both short and long films achieve varying levels of financial success.
  
  

