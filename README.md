# Lok-Sabha-Election-2019-Data-Analysis

# Introduction
The Lok Sabha Election 2019 Data Analysis project aims to analyze election data, focusing on candidate assets, party performance, and statistical insights. Using Python and data science techniques, this project explores various aspects of the 2019 Indian general elections.

# Objectives
Perform statistical analysis on election data.
Verify claims about candidate assets using hypothesis testing.
Visualize election trends and patterns.

# Dataset
The project uses a dataset named Lok+Sabha_2019.csv, which contains the following key columns:
STATE: The state from which the candidate contested.
CANDIDATE: Candidate's name.
PARTY: Political party affiliation.
ASSETS: Declared assets of the candidate.
LIABILITIES: Declared liabilities.
CRIMINAL_CASES: Number of criminal cases against the candidate.
VOTES: Total votes received.
WINNER: Indicates if the candidate won (1) or lost (0).

# Methodology

1.Data Preprocessing :
Load the dataset using pandas.
Clean missing and inconsistent values.
Convert necessary columns into numerical formats for analysis.

2.Exploratory Data Analysis (EDA) :
Summary statistics of candidates, assets, and party performances.
Visualizations using Matplotlib and Seaborn.
Distribution of assets and liabilities across different states.
Hypothesis Testing: Bihar Candidates' Assets
Claim by ADR: The average assets of Bihar candidates in 2019 were higher than in 2014 (5 crores).

3.Hypotheses :
Null Hypothesis (H0): Avg. assets for a Bihar candidate ≤ 5 crores.
Alternate Hypothesis (H1): Avg. assets for a Bihar candidate > 5 crores.

4.Statistical Test :
One-sample t-test using scipy.stats.ttest_1samp().
Alpha level: 0.05 (5% significance level).

5.Results & Insights :
Interpretation of the hypothesis test results.
Political trends and key observations.
Distribution of assets and liabilities among different parties.

6.Technologies Used :
Python: Core programming language.
Pandas & NumPy: Data manipulation and analysis.
Matplotlib & Seaborn: Data visualization.
Scipy: Statistical analysis.

# Conclusion
This project provides valuable insights into the 2019 Indian general elections by analyzing candidate data and performing hypothesis testing. The findings help understand electoral trends and financial backgrounds of candidates.

# Future Scope
Expanding analysis to include more elections (e.g., state elections).
Sentiment analysis of election speeches and social media.
Predictive modeling for future election outcomes
