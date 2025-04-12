Car Price Prediction using Linear Regression 🚗📈
This project applies Linear Regression to predict car prices based on various features from a dataset.

Dataset 📂
The dataset contains specifications of different cars like:

make

fuel-type

num-of-doors

horsepower

engine-size

curb-weight

price ...and more.

Note: Some missing values were represented with ? in the dataset.

Data Preprocessing 🛠️
Replaced all ? marks with null values.

Filled missing values:

Numerical columns ➔ filled using the mean.

Categorical columns ➔ filled using the mode.

Encoded categorical variables using Label Encoding / One Hot Encoding to make data suitable for machine learning models.

Model 🧠
Applied Linear Regression to predict car prices.

Split the data into training and testing sets.

Evaluated model performance using:

Mean Squared Error (MSE)

R² Score
