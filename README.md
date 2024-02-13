# Feature Engineering 

## Label Encoding and OneHot Encoder

Introduction:

In the realm of predictive modeling and machine learning, encoding categorical variables is a crucial step in preparing data for analysis. Categorical variables, such as "town" in our dataset, represent qualitative data and cannot be directly used in mathematical models. Therefore, they need to be converted into numerical representations that machine learning algorithms can handle.

Two common encoding techniques are Label Encoding and OneHot Encoding. Label Encoding assigns a unique integer to each category, while OneHot Encoding creates binary columns for each category, representing its presence or absence. Description:

In this scenario, I conducted an experiment where i applied Label Encoding and OneHot Encoding to the "town" variable in a dataset containing information about housing prices. The dataset also includes the "area" variable as a predictor of housing prices.

After encoding the categorical variable, we built two separate linear regression models:

Model 1: Label Encoding

Model 2: OneHot Encoding

Evaluated the performance of each model by examining their R-squared values, which measure the proportion of the variance in the dependent variable (price) that is predictable from the independent variables (features). A higher R-squared value indicates a better fit of the model to the data.
