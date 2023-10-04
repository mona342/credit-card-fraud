# credit-card-fraud
The Python code is being used to analyze a dataset on credit card fraud.
1. Importing the Required Libraries:
The necessary libraries are imported, including NumPy for numerical computations, Pandas for data manipulation and analysis, Matplotlib and Seaborn for data visualization, and Gridspec for creating multi-plot grids.

2. Loading the Dataset:
The credit card fraud dataset is loaded from a CSV file using the read_csv() function provided by Pandas.

3. Exploring the Dataset:
To understand the dataset, the columns are printed using the print(data.columns) statement. Additionally, the describe() function is utilized to obtain a statistical summary of the columns. For faster processing, a sample of the dataset is extracted using the sample() function.

4. Visualizing the Dataset:
Data distribution is visualized by plotting histograms for all the columns using the hist() function. Furthermore, a correlation matrix is created using the heatmap() function from the Seaborn library to identify correlations among different dataset features.

5. Preprocessing the Dataset:
The dataset is divided into input features (X) and output variable (Y). The data is then split into training and testing sets using the train_test_split() function from the sklearn library.

6. Building a Random Forest Model:
A random forest classifier is constructed using the RandomForestClassifier() function from the sklearn library. The model is trained on the training data using the fit() function, and predictions are made on the test data using the predict() function.

7. Evaluating the Random Forest Model:
Several performance metrics, including accuracy, precision, recall, F1-Score, and Matthews correlation coefficient, are calculated using the corresponding functions provided by the sklearn.metrics module. Additionally, the confusion matrix is plotted using the heatmap() function from the Seaborn library.
