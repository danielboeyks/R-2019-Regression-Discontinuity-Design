# R-Regression-Discontinuity-2019
Causal Analysis in Regression Discontinuity Design (R, 2019)

This R file contains a replication project of the following paper:
Sanz, C. (n.d.). Direct democracy and government size: Evidence from Spain. Political Science Research and Methods, 1-16. doi:10.1017/psrm.2018.65

The dataset can be found here:
https://www.cambridge.org/core/journals/political-science-research-and-methods/article/direct-democracy-and-government-size-evidence-from-spain/E3D106AD332D40789DECC98090EFBA90#fndtn-supplementary-materials

Abstract:
Sanz (2018) studies the effect of direct democracy on economic policy, namely: revenues, expenditures and deficits. In this study, he used a fixed-effect regression discontinuity design (RDD), controlling for municipality and time fixed effects. According to his models, direct democracy leads to a smaller government, reduces public spending by ~8%, reduces revenues by ~6% but had no statistically significant effect on budget deficits. 

In this report, I aim to replicate the results as laid out in the paper and aim to further the discussion of the results in the paper with modifications to the model. In this paper, Chapter 3 replicates Table 1 and Figure 2 in Sanz's paper. Chapters 4 to 6 aim to replicate the results for Table 2 and Figure 3. In Chapter 7, I investigate the covariate balance within the optimal bandwidths and compare hypothetical results should conditioning on these covariates be necessary. Thereafter, in Chapter 8, I estimate the LATE of revenues and expenditures without logarithms and found no statistically significant effect of Direct Democracy. Last, in Chapter 9, I used the World Bank's GDP deflators for Spain and estimated the sensitivity of LATE to higher and lower GDP deflators.
