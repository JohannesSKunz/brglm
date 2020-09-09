# brglm
Bias Reduced Generalized Linear Model Estimator
Johannes S. Kunz, Kevin E. Staub, Rainer Winkelmann 

version 1.0 

Stata program to estimate bias-reduced glm models Kosmidis and Firth (2009) can be alternatively installed using ssc install brglm in Stata

brglm estimates bias-reduced probit, logit and cloglog models by iterative weighted least squares (IWLS).

    - Cross-sectional properties are derived by Kosmidis and Firth (2009).

    - Panel models with fixed effects can be estimated by including an indicator variable for each panel unit
    as shown by Kunz, Staub and Winkelmann (2017).


References: 

Kosmidis, Ioannis & David Firth. 2009. 
        ‘Bias reduction in exponential family nonlinear models.’  Biometrika, 96(4):793–804.

Kunz, Johannes S., Kevin E. Staub & Rainer Winkelmann. 2017. 
        ‘Estimating fixed effects: Perfect prediction and bias in binary response panel models, 
        with an application to the Hospital Readmissions Reduction Program.’  SSRN Working Paper No. 3074193.
