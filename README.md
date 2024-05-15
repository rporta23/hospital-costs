# Predictive Analysis of Hospital Costs: A Comparative Study of Statistical Learning Techniques

Final report [here](https://github.com/rporta23/hospital-costs/blob/main/finalreport.pdf)

# Contributers:
- [Lindsay Knupp](https://www.linkedin.com/in/lindsay-knupp-3a230916a/)
- [Rose Porta](https://www.linkedin.com/in/rporta23/)
- [Johnny Rasnic](https://www.linkedin.com/in/johnny-rasnic-302a35223/)

# Abstract

The purpose of this analysis is to understand the relationships between certain characteristics of hospitals like location, number of full time equivalent employees, or number of beds, for example, with the hospitals' total operating costs. Further, we aim to compare the efficacy of several different statistical learning techniques in predicting total costs given the predictors.

Our data was collected from [Centers for Medicare & Medicaid Services](https://data.cms.gov/provider-compliance/cost-report/hospital-provider-cost-report) on April 03, 2024. It features information about hospitals through annual cost reports in $2020$. It had $5712$ observations; $90\%$ were used as our training set and $10\%$ were used as our test set. To perform qualitative analyses, we categorized each hospital as above or below the median total costs.

We found that salaries was one of the most important predictors across all our analyses. This is interesting as salaries is the only predictor which is a direct component of the total costs. This implies that a large part of the variability in hospital costs can be explained by salaries.  

Further, we found it interesting that all methods had similar error rates ranging from simpler to more complex models. Although we found improvements in the methods including all the predictors, even the simple models including one predictor did not perform much worse than the full models.

In our simulation study, we discovered variability in our optimal choice of $k$ in the KNN method. It was surprising that the error rate was not influenced much by the choice of $k$ when trying $k \in [1,100]$. Most of the selected $k$ values ranged from $[1,25]$ but some simulations yielded much higher values of $k$. 

