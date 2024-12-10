# Regression
- What can mean & regression do that other statistical measures don't?
	- Mean & Regression can both aid in predicting future outcomes
- Why can't I just use the mean?
	- Mean by itself has a characteristic that decision makers want to minimize - variability
	- Why does this matter?
		- Variability cause prediction errors - and prediction errors cause poor business decisions
	- Mean also does not 
		- Indicate the significant relationships between dependent and independent variables
		- Indicate the level of impact that multiple independent variables have on a dependent variable
		- Allow for comparing the effect of variables measured on different scales (i.e. effect of tax increases against the number of trips to the store)

- Definition: Predictor of future outcomes that can be accomplished via
	- Analysis of the relationship between a dependent variable and one or more independent variables with the goals of
	- Identifying the pattern that most accurately represents the particular data set being analyzed AND
	- Minimizing prediction error

- Most common type of Regression is called Linear Regression
	- Formula y = aX1 + aX2 . . . . aXn + b
	- The dependent variable is y, the independent variable(s) is X, the slope is a, and the y-intercept is b

- How to interpret output of Linear Regression
	- Two Primary Numbers
		- R Square or Adjusted R Square
			- Won't have negative
			- 0 means very poor fit
			- .9 or .8 mean very good fit, even .6 or .7 means you can address more than half scenarios
			- .5 means only predicting half the time
			- **Under .20 (20%) poor predictor, do not make predictors on this!**

- Other types of regression include:
	- Logarithmic
	- Polynomial
	- Exponential
	- Power
	- Ridge
	- LASSO
	- ElasticNet
	- and More

- Multiple R 