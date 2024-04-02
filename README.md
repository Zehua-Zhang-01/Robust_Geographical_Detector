# Robust_Geographical_Detector
Code and explanations for the statistical method - 'Robust Geographical Detector' (with Gold Open Access) https://doi.org/10.1016/j.jag.2022.102782

The article 'Robust Geographical Detector' released in 2022 was my first research publication. This is an improved statistical analysis techniques in assisting (1) find statistical associations between variables, and (2) show some spatial patterns / features through statistical groups. The method was built based on 'A measure of spatial stratified heterogeneity' (https://doi.org/10.1016/j.ecolind.2016.02.052)

Q: Why 'Robust Geographical Detector' is different?

A: We introduced an optimization algorithm - 'Change point detection' to find optimal statistical groups that could tell the maximum statistical associations between variables. The input one-dimensional series is the dependent variable values sorted by the rank of independent variable. 

Q: How to use it?

A: Please find the .ipynb file. After running the code, you will get a new column in a new file telling results generated from the change point detection. If you wanna see the 'q-value', please use the GD package in R (https://cran.r-project.org/web/packages/GD/GD.pdf) in your following steps. Please be noted that we now have a categorial type of X-variable already, and there is no need to classify. 

Ackowledgement: I was inspired by the release of 'ruptures' Python (https://centre-borelli.github.io/ruptures-docs/) and the review article 'Selective review of offline change point detection methods' (https://doi.org/10.1016/j.sigpro.2019.107299)

Please let me know if there are issues. Thanks for your support. 
