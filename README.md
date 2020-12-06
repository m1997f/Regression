# Regression
Thanks to [Hadelin de Ponteves](https://www.udemy.com/user/hadelin-de-ponteves/), In this project, I examined the regression models (Multiple Linear Regression, Polynomial Regression, Support Vector Regression, Decision Tree Regression and Random Forest Regression) to find out the best model for my dataset given UCI Machine Learning Repository. For evaluating Regression models performance, I used R-squared method by importing it from sklearn library, metrics module, [r2_score class.](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html#sklearn.metrics.r2_score)</br>
## Dataset
This dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years and we want to try to predict an energy output without understanding how it works or science behind the energy. For predicting it we have 4 features which are:</br>
**1-** AT : ambient Temperature in the range 1.81°C and 37.11°C</br>
**2-** V : Exhaust Vacuum  in the range 25.36-81.56 cm Hg</br>
**3-** AP : Ambient Pressure in the range 992.89-1033.30 milibar</br>
**4-** RH : Relative Humidity in the range 25.56% to 100.16%
