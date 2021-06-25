# brglm
Bias Reduced Generalized Linear Model Estimator
Johannes S. Kunz, Kevin E. Staub, Rainer Winkelmann 

- Current version: `1.0.1 25jun2021`
- Jump to: [`overview`](#overview) [`update history`](#update-history) [`references`](#references)

-----------

## Overview 

Stata program to estimate bias-reduced glm models Kosmidis and Firth (2009) can be alternatively installed using ssc install brglm in Stata (v1.0.0)

brglm estimates bias-reduced probit, logit and cloglog models by iterative weighted least squares (IWLS).

    - Cross-sectional properties are derived by Kosmidis and Firth (2009).

    - Panel models with fixed effects can be estimated by including an indicator variable for each panel unit
    as shown by Kunz, Staub and Winkelmann (2021).
    
**Note**: [brfeglm](https://github.com/JohannesSKunz/brfeglm) provides a new version of this command that is much faster and user friendly.


## Update History
* **Nov 14, 2017**
  - initial commit
* **Jun 25, 2021**
  - correction printed log-likelihood value

## References: 

Kosmidis, Ioannis and David Firth. 2009. 
        ‘Bias reduction in exponential family nonlinear models.’  Biometrika, 96(4):793–804.

Kunz, Johannes, Kevin E. Staub, and Rainer Winkelmann. 2021. Predicting Individual Effects in Fixed Effects Panel Probit Models. Journal of the Royal Statistical Society: Series A. Forthcoming.
