Project Description

The Wine Quality Prediction System is a data science project that analyzes the physicochemical properties of wine and predicts whether the wine is of good quality or not using machine learning techniques. The project uses a dataset containing various chemical attributes of wine such as acidity, sugar level, alcohol content, pH level, sulphates, and density. These features are used to train a model that can automatically classify wine quality.

The dataset is first explored and visualized to understand the distribution of wine quality. The quality values are then converted into a binary classification problem where wines with a quality score greater than or equal to 7 are considered good, while others are labeled as not good. The data is divided into training and testing sets to evaluate the performance of the model.

A Random Forest Classifier is used to train the prediction model after applying feature scaling using StandardScaler. The trained model is evaluated using accuracy score, confusion matrix, and classification report to measure its performance. Additionally, feature importance visualization is used to identify which chemical properties contribute most to determining wine quality.

Finally, the system allows prediction for new wine samples by inputting their chemical attributes, enabling the model to determine whether the wine is likely to be of good quality or not. This project demonstrates practical applications of data preprocessing, visualization, machine learning model training, and predictive analytics using Python and Scikit-learn.
