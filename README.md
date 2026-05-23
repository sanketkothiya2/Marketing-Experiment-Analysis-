# Marketing Campaign Analysis: A/B Testing and Regression Analysis

## Overview
This project analyzes the performance of two digital advertising platforms, Facebook Ads and AdWords, using a marketing campaign dataset from 2019. The goal is to help a marketing agency identify the most effective platform for improving clicks, conversions, and cost efficiency.

The work is based on a guided data analysis project and a tutorial video:

- Video reference: https://www.youtube.com/watch?v=iCj4lT5KvJk
- Dataset and notebook are stored in the `Marketing Campaign/` folder

## Business Problem
The agency needs to know which platform delivers better campaign performance so it can allocate budget more effectively and improve return on investment.

## Project Goals
- Compare Facebook Ads and AdWords performance
- Analyze clicks, conversions, and cost-related metrics
- Use A/B testing to determine whether one platform performs significantly better
- Build a regression model to estimate expected conversions from clicks
- Review weekly and monthly trends for better decision-making
- Present the findings in a simple way for non-technical stakeholders

## Dataset
The project uses a CSV file with daily marketing campaign data for 2019.

Expected project assets:

- `Marketing Campaign/marketing_campaign.csv`
- `Marketing Campaign/AB Testing (Marketing Campaigns).ipynb`

## Analysis Workflow
The notebook follows a step-by-step workflow:

1. Data loading and cleaning
   - Import Python libraries for data analysis, visualization, statistics, and modeling
   - Convert date values to datetime format
   - Clean percentage and currency fields so they can be analyzed numerically

2. Exploratory data analysis
   - Review summary statistics
   - Plot distributions for clicks and conversions
   - Compare average daily campaign performance

3. Conversion grouping and comparison
   - Group conversion counts into categories
   - Compare how often each platform falls into low and high conversion ranges

4. Correlation analysis
   - Check whether higher clicks are associated with higher conversions
   - Visualize the relationship using scatter plots and correlation metrics

5. A/B testing
   - Run an independent t-test to compare average conversions between Facebook Ads and AdWords
   - Use the test result to support a platform recommendation

6. Regression analysis
   - Train a linear regression model with clicks as the predictor and conversions as the target
   - Evaluate the model using metrics such as mean squared error and R-squared

7. Time-based analysis
   - Analyze conversion trends by month and weekday
   - Review cost per conversion across time periods

8. Cointegration test
   - Check for a long-term relationship between advertising spend and conversions

## Key Questions Answered
- Which advertising platform performs better overall?
- Do more clicks lead to more conversions?
- Are there specific days or months with stronger performance?
- How accurately can conversions be predicted from clicks?

## Tools and Libraries
Typical libraries used in the notebook include:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Repository Structure
```text
project-1-Marketing Campaign Analysis AB Testing and Regression Analysis/
├── Marketing Campaign/
│   ├── AB Testing (Marketing Campaigns).ipynb
│   └── marketing_campaign.csv
├── README.md
├── .gitignore
├── project guidline.txt
└── 
```

## How to Run
1. Open the `Marketing Campaign/AB Testing (Marketing Campaigns).ipynb` notebook in Jupyter or VS Code.
2. Make sure the required Python packages are installed.
3. Run the notebook cells from top to bottom.
4. Review the plots, statistical tests, and regression outputs.

## Notes
- The notebook has not been executed in the current workspace snapshot.
- The analysis is intended to support a business recommendation, not just a technical model score.
