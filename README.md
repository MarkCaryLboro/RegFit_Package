# RegFit_Package

MATLAB RIGLS Algorithm

by 

Mark Cary

Implements general nonlinear regularised iterative least squares algorith, with optimal hyper-parameter selection.

1. Hyper-parameter selection based on fixed point iteration at each step of the nonlinear search.
2. Hyper-parameter selection based on information theoretic criterion, either AICc or BIC.
3. Supports heteroscedastic or iid data.
4. Can add in any custom fit model or covariance model.
5. Can implement custom information criterion for hyper-parameter selection.
6. Supports bootstrapping and confidence interval generation.
7. Model diagnostic plots created.
8. User documentation available, including installation instructions.

Issues

1. hasm class not complete
2. Does not support serially correlated data

Future Enhancements

1. Support serially corellated data for time series analysis
2. Implement block bootstrapping tool
3. Add higher order regularisation functionals

Version 2.0 Enhancement 04/06/2020 by M. Cary

1. Added bspm (B-spline model class). Data must be coded onto the interval X--> [0, 1]. It is recommended Y-data are coded onto the same interval.
   RegFitUserNotes.doc has been updated to reflect bspm usage.
