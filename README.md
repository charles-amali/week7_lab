# Health-EDA
## Libraries used
1. Pandas
2. LabelEncoder 
3. Matplotlib
4. Seaborn

## Loading the dataset
- The dataset was loaded from the CSV file using pandas library.
- The CSV file is located in the main directory.

## Inspecting the dataset
- The dataset was inspected to understand its structure and content. 
- The head() function was used to display the first five rows of the data.
- The info() function was used to display information about the data, such as the number of non -null values in each column.
- The describe() function was used to display summary statistics for the data.

## Data Cleaning
- All the data type of the columns in the dataset were float which made sense because all the values in those column were numeric.
- The only columns which were of the datatype object were "ca" and "thal". There were numeric values in these column.
- The datatype was object because there were some missing values which was represented by "?".
- For Pandas to recognize this as a missing value, it had to be replaced with a "NaN" value (Indicating null).
- Then the columns converted to float datatype. The missing values in the "ca" and "thal" column were both replaced with the mode of the respective column.
- The mode is the most frequently occurring value in the column. There were no duplicates.

## Univariate Analysis
- Visualized the distribution of numerical variables using histograms and box plots.
- The distribution of the variables "age", "trestbps", "chol", "thalach", "oldpeak", were visualized.
- The distribution of the variables "sex", "cp", "ca", "thal" were visualized using bar plots.
- The findings can be found in the notebook beneath each variable analysis

## Bivariate Analysis
- Visualized the relationship between numerical variables using scatter plots.
- The relationship between numerical and categorical variables was visualized using boxplots and the relationship between Categorical and categorical relationships using crosstab.

## Multivariate Analysis
- Pairplots was used to visualized multiple relationships

NB:
Overall finding can be seen in the notebook
