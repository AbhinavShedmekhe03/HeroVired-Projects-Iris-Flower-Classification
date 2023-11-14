# Iris Flower Classification Project

## Project By
Abhinav Shedmekhe

## Aim
The aim of the Iris Flower Classification Project is to develop a machine learning model that can accurately classify iris flowers into different species based on their sepal length, sepal width, petal length, and petal width. The project utilizes the famous Iris dataset, a well-known dataset in the field of machine learning.

## Project Description
The Iris Flower Classification Project involves building a machine learning model to classify iris flowers into three species: setosa, versicolor, and virginica. The project uses the Iris dataset, which consists of measurements of sepal length, sepal width, petal length, and petal width for 150 iris flowers, with 50 samples from each of the three species.

### Workflow:

1. **Data Import and Exploration:**
   - Libraries such as pandas, numpy, sklearn, matplotlib, and seaborn are imported.
   - The Iris dataset is loaded, and its metadata is explored using the `load_iris` function.
   - A DataFrame is created from the dataset, and exploratory data analysis (EDA) is performed.
   - The 'Species' column is renamed for better readability.

2. **Exploratory Data Analysis (EDA):**
   - Information about the dataset is displayed using `df.info()`.
   - Descriptive statistics, including mean, standard deviation, minimum, and maximum values, are obtained using `df.describe()`.
   - The distribution of iris species in the dataset is visualized using `df['Species'].value_counts()`.
   - Histograms and scatter plots are created to visualize the distribution and relationships between different features.

3. **Data Preprocessing:**
   - The dataset is split into training and testing sets using the `train_test_split` function.

4. **Model Building:**
   - Logistic Regression is chosen as the classification algorithm.
   - The model is trained using the training set (`x_train` and `y_train`).

5. **Model Evaluation:**
   - The trained model is used to predict iris species on the test set (`x_test`).
   - Accuracy, confusion matrix, and a classification report are generated to evaluate the model's performance.

6. **Results Visualization:**
   - A heatmap of the confusion matrix is plotted for better visualization.
   - The classification report is presented as a heatmap for a comprehensive view of precision, recall, and F1-score.

This project serves as a practical example of classification using machine learning techniques and provides insights into the Iris dataset. The final model can be used to predict the species of iris flowers based on their morphological characteristics.
