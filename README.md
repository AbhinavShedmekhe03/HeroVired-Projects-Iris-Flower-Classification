# IRIS Flower Classification Project

**Project By:** Abhinav Shedmekhe

**Aim:**
The aim of this project is to build a machine learning model for classifying iris flowers into different species based on their sepal length (SL), sepal width (SW), petal length (PL), and petal width (PW).

**Project Description:**
This project involves the following key steps:

1. **Importing Required Libraries:**
   - Pandas, NumPy, Seaborn, Matplotlib, and Scikit-learn are imported for data manipulation, visualization, and machine learning tasks.

2. **Importing Dataset:**
   - The iris dataset is loaded using Scikit-learn's `load_iris` function.

3. **Creating DataFrame:**
   - The dataset is converted into a pandas DataFrame for easy manipulation.

4. **Renaming Species and Columns:**
   - Species and column names are renamed for better readability.

5. **Exploratory Data Analysis (EDA):**
   - Information about the dataset is displayed using `df.info()` and descriptive statistics using `df.describe()`.
   - The count of each species is checked using `df['Species'].value_counts()`.
   - Histograms and scatter plots are created for visualizing the distribution and relationships between variables.

6. **Building Model:**
   - The dataset is split into training and testing sets.
   - A logistic regression model is trained using the training data.

7. **Model Evaluation:**
   - The model is evaluated on the test data using accuracy, confusion matrix, and classification report.

**Summary:**
The project successfully achieves the classification of iris flowers with a high accuracy score of 98%. The logistic regression model demonstrates excellent performance in distinguishing between different iris species based on their sepal and petal characteristics.
