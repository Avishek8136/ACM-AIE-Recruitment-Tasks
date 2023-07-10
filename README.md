# Avishek_Rauniyar_S2
# AIE Recuritment Tasks
## Imported Dependencies
1. matplotlib
2. pandas
3. seaborn
4. Numpy
5. sklearn

## Loading dataset with pandas 
Source : [Click Here](https://www.kaggle.com/datasets/epa/air-quality)

## Statistical Analysis of the Dataset:
Statistical analysis is the process of collecting and analyzing large volumes of data in order to identify trends and develop valuable insights.
dataset.head() : To get head elements of the dataset with 5 rows
dataset.describe() : To generate descriptive statistics that summarize the central tendency, dispersion and shape of a dataset’s distribution, excluding NaN values.

## Plotting the datset
Using matplotlib the following graphs were plotted
1. year vs fifty_percentile (Line Plot)
2. year vs seventy five percentile (Line Plot)
3. Comparison between State Name and Fifty Percentile (Line Chart)
4. Comparison between year and seventy file percentile (Scatter Plot)

## Checking Null values and removing null rows
dataset.isnull().sum() : Gives number of Null values of each columns
dataset.dropna() : Drop null values

## Standardization of the dataset
Dividing the data into test data and train data using test_train_split from sklearn.processing
using Standard Scaler to standardize the training dataset

## Displaying the correlation matrix
Selected some features and find the correlation matrix accordingly using .corr() function of pandas library

## Trained the model using RandomForestRegressor
imported RandomForestRegressor from sklearn and trained the model using train data

## Standardizing the test data
Converting the test data and converting it into same scale

## Predicted the output on testing set
## Finding the mean absolute error
importing mean_absolute_error of slearn library the mean absolute error was found out
