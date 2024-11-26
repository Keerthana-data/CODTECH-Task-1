name-Keerthana B
company- CODTECH IT SOLUTIONS
ID-CT08DS9362
Duration-oct 30th to nov 30th 


OVER VIEW 
This code performs the following EDA tasks:

1. Loads the Iris dataset
2. Views the first few rows of the dataset
3. Checks for missing values
4. Gets the summary statistics of the dataset
5. Visualizes the distribution of each feature using histograms
6. Visualizes the correlation between features using a heatmap
7. Visualizes the relationship between features using scatter plots
8. Identifies outliers using box plots
 
 
 
 OUTPUT
sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)  target
0                 5.1               3.5               1.4               0.2       0
1                 4.9               3.0               1.4               0.2       0
2                 4.7               3.2               1.3               0.2       0
3                 4.6               3.1               1.5               0.2       0
4                 5.0               3.6               1.4               0.2       0


- df.isnull().sum(): Checks for missing values in the DataFrame.


sepal length (cm)    0
sepal width (cm)      0
petal length (cm)     0
petal width (cm)      0
target                  0
dtype: int64


- df.describe(): Generates summary statistics for the DataFrame.


       sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)
count          150.000000         150.000000           150.000000          150.000000
mean              5.843333            3.054000             3.758667            1.198667
std               0.828074            0.433594             1.765298            0.763902
min               4.300000            2.000000             1.000000            0.100000
25%               5.100000            2.800000             1.600000            0.300000
50%               5.800000            3.000000             4.350000            1.300000
75%               6.400000            3.300000             5.100000            1.800000
max               7.900000            4.400000             6.900000            2.500000
