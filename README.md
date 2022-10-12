# Prosper Loan Data Exploration


## Dataset

The data consists of information regarding Prosper Loan listings, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found [here](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1663726254748096&usg=AOvVaw2BUEeLRX9Tve55hr8WUB1N), and the data dictionary [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1663726254749247&usg=AOvVaw1f2xc0weUncJxA541_W2a0).

## Summary of Findings

In the exploration, I found that the distribution of the loan outcome was generally good, with a large proportion of the loans completed. When looking at the effect of the loan amount and interest rate on the loan outcome, I found that a decrease in the loan amount and a decrease in the interest rate tend to result in a much better loan outcome. When I extended the multivariate exploration by introducing Prosper Score; _(a custom risk score based on historical Prosper data)_ into the mix, I found that listings with a high prosper score, low interest rate and not so high loan amount (<=$7,000) seems to be completed more than other listings, while listings with very low prosper scores, high interest rate and low loan amount seems to be chargedoff more than other listings.

It was interesting to find out that listings high Prosper Score had much more lower interest rate than listings with low Prosper Score. 


## Key Insights for Presentation

For the presentation, I focused on the influence of Loan Amount, Interest Rate and Prosper Score on Loan Outcome. I start by introducing the distribution of loan outcome, followed by the pattern in loan amount distribution, then the pattern of the distribution of interest rate. 

Afterwards, I looked at the effect of loan amount and interest rate on the outcome of the loans, and I went further by looking at how prosper score would influence that effect.