# Covid19

This work is an analysis of Covid-19 case counts and deaths in California in early 2020. A number of statistical modeling techniques are applied and regional effects are considered. There are three separate analyses which are described below.

CovidCountyAnalysis1:

  In this work we consider three different models to answer the question: If 20% of California residents contract Covid-19, what is the probability that more than 200,000 people will die? The first model uses a Binomial likelihood with a Beta prior and a single state-wide mortality rate. We consider a variation on this model with a BetaBinomial likelihood to account for overdispersion in the data.  Finally we consider a hierarchical Binomial model where mortality rate can vary accross counties.
  
CovidCountyAnalysis2:

  In this work we develop models to predict the number of cases and deaths per 1000 habitants in each county of California. We use a hierarchical exposure weighted poisson model with Gamma prior distributions.
  
RegionalEffectsOfCovid19:

  The goal of this analysis is to determine whether census regions have a strong effect on Covid-19 cases, as well as how population density effects case counts. We use standard Bayesian linear regression with g-priors for shrinkage in regression estimates.
