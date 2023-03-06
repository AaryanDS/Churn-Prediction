#Churn Prediction
This project aims to predict customer churn for a telecommunications company using machine learning techniques. The dataset used for this project is publicly available from Kaggle, and contains information on customer demographics, account information, and service usage.

##Files
Churn_Prediction.ipynb: Jupyter notebook containing the code for the project.
telecom_churn.csv: Dataset used for the project.
Libraries Used
The following Python libraries were used for this project:

Numpy
Pandas
Matplotlib
Seaborn
Scikit-learn
Approach
The project involved the following steps:

Data Cleaning and Preprocessing: The dataset was cleaned and preprocessed to handle missing values and convert categorical variables into numerical representation using one-hot encoding.
Exploratory Data Analysis: The relationships between variables were analyzed to identify important features for the model.
Model Building: A Random Forest Classifier model was built and trained on the preprocessed data to predict customer churn.
Model Evaluation: The model was evaluated using various performance metrics, including accuracy, precision, recall, and F1 score. Confusion matrix was also used to analyze the model's predictions and identify areas for improvement.
Results
The Random Forest Classifier model achieved an accuracy of 92% on the test data, indicating its effectiveness in predicting customer churn. The most important features for the model were found to be the number of customer service calls made and the international plan subscribed by the customer.

Conclusion
The project demonstrates the effectiveness of machine learning techniques in predicting customer churn for a telecommunications company. The insights gained from this project can be used to develop targeted marketing strategies and retention programs to reduce customer churn and increase revenue.
