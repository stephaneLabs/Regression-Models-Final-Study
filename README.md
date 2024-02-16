Abstract
This is a study based on the mtcars data from the R software, trying to determine the influence of the transmission type (Manual vs Automatic) on the consumption (mpg) of the cars. This is the last assignment graded by peers to pass the certificate of the Coursera course “Regression Models” taught by Dr Brian Caffo, Dr Roger D. Peng and Dr Jeff Leek from John Hopkins University. We here performed a backward elimination of the predictors modelling the consumption “mpg” starting with all the predictors possible in the data set. This way we got a more parsimonious model and we tried to get it better by adding it the interactions terms of transmission with weight (am:wt) and transmission with horsepower (am:hp). This ancova model that we fitted had an adjusted R-squared of 0.87 with residuals reasonably following a normal distribution. Our model showed Manual cars had a +14.9 miles/gallon significant effect and showed an interaction slope “am:wt” of -5.21 for Manual cars : on the whole, Manual cars consume less but as their weight grows up they will comparatively consume more than Automatic ones.

References
* Caffo B et al (2024) : Regression Models - Online course on Coursera from John Hopkins University
* Fox J, Weisberg S (2019). An R Companion to Applied Regression, Third edition. Sage, Thousand Oaks CA. https://socialsciences.mcmaster.ca/jfox/Books/Companion/.
* Le S, Josse J, Husson F (2008). FactoMineR: An R Package for Multivariate Analysis. Journal of Statistical Software, 25(1), 1-18. 10.18637/jss.v025.i01
* R Core Team (2023). R: A Language and Environment for Statistical Computing. R Foundation for Statistical Computing, Vienna, Austria. https://www.R-project.org/.