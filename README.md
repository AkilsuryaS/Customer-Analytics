# Customer-Analytics: Project 1

### Datasets
• billboard.csv
• khakichinos.csv 
• books.csv

### Models used:
* **Poisson Model** - A statistical model that describes the number of events occurring within a fixed interval of time or space. It assumes that these events happen independently of each other and at a constant average rate. The Poisson distribution is used to model count data.
* **Negative Binomial Distribution Model** - A statistical model that extends the Poisson model to account for over-dispersion, where the variance exceeds the mean. The NBD model introduces a parameter to handle this extra variability, making it suitable for count data with more dispersion than the Poisson model can handle.
* **Poisson Regression Model** - A type of generalized linear model (GLM) used to predict a count dependent variable based on one or more independent variables. It assumes the response variable follows a Poisson distribution, and the logarithm of its expected value is a linear combination of the predictor variables.
* **NBD Regression Model** - Similar to the Poisson regression model but used when the count data shows over-dispersion. It incorporates an extra parameter to account for the greater variability, providing a more flexible approach for modeling count data when the Poisson assumptions do not hold.

### Task
To write a code for the following models and predict it's MAximum Likelihood Estimation (MLE), compare between models and explain which is better and why. Also, provide some managerial takeaways if possible.

# Customer-Analytics: Project 2

### Datasets
• candy.csv
• articles.csv

### Models used:
**(a) the Poisson model**
(b) the NBD model,
(c) the Zero Inflated NBD model, and
(d) Finite Mixture models for 2, 3, and 4 segments.
