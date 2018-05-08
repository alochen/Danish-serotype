# Danish-serotype
JAGS code for hierarchical model of serotypes. jags_model.R contains the JAGS model itself. "run model.R" loads data, processes data, and plots output 

Note that the data provided are NOT observed numebrs of cases. These are drawn from a Poisson distribution, where the mean is equal to the model fitted value for the corresponding serotype/age group/comorbidity level/epi-year. therefore, using these data with the provided code will give answer similar to, but not equal to the estimates from the paper.

Figure S6: Observed vs expected incidence of IPD for each serotype, age groups, comorbidity-level stratification. Dots indicate observed values, black line indicates the fitted value, red line +/- 95% CI indicates expected incidence in the absence of vaccine. 

