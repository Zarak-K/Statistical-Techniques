The purpose of these notebooks is to show how the validity of different models can be assessed when fit to a dataset. This is important as the parameters of a well-fit model can reveal relationships between the quantities under investigation. Additionally, models can provide predictive power over the outcomes of unseen data.

The dataset used in "Bootstrap.ipynb" relates to the activity of a radioactive isotope as a function of time. An exponential decay fit is applied to the data with free parameters of initial activity and decay constant. Bootstrapping is used to estimate best fit parameters and uncertainties, and the isotope is identified by calculating its half-life from the best fit decay constant.

The dataset used in "Assessing Models.ipynb" relates to the activity of a source containing multiple isotopes as a function of time. In this case, a model assuming one isotope is present in the source is fit to the data, followed by a model assuming two isotopes. The best fit parameters with uncertainties for the single isotope model are determined using a chi-squared grid method, and for the dual-isotope model, the Markov Chain Monte Carlo (MCMC) method implementing the Metropolis-Hastings algorithm is used. The validity of each model is then assessed using the Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC), and this information is used to infer how many isotopes are present in the sample. The isotopes are then identified by calculating their half-lives from best fit decay constants, although, this information needs to be interpreted with caution given the high degree of correlation between model parameters.
