# Implementation-of-Logistic-Regression-Algorithim
<br>
Libraries Import: The notebook begins by importing necessary libraries such as NumPy, Pandas, Seaborn, and Matplotlib.
<br>
Dataset Loading: It fetches the Titanic dataset using fetch_openml and stores it in a DataFrame.
<br>
Logistic Regression: The notebook uses the Logistic Regression algorithm to build a predictive model.
<br>
The notebook likely evaluates the model using common metrics associated with Logistic Regression, such as:

<br>
Accuracy: The percentage of correctly predicted instances out of the total instances.
<br>
Confusion Matrix: A table used to describe the performance of a classification model.

<br>
Several visualizations, including count plots and histograms, are used to explore the dataset, particularly focusing on survival rates, passenger classes, and age distribution.
Missing values are identified and analyzed.

<br>
Feature Engineering:
<br>
The notebook creates new features like "family" and "travelled_alone" based on existing ones like sibsp and parch.
It also drops unnecessary columns such as name, ticket, home.dest, body, boat, and cabin.

<br>
Data Preprocessing:
<br>
OneHotEncoding is applied to the sex column.
Missing values in columns like age and fare are imputed using the mean, and categorical missing values are imputed using the most frequent strategy.
