# LinearRegression_Iris_dataset
To perform classification on Iris dataset using linear regression.

ABOUT DATASET
The dataset is called the “Iris Dataset”, which consists of 150 data points, divided into 3 classes, each having 50 data points. The 3 classes are- Iris_Setosa, Iris_Versicolor, Iris_Virginica.
For every data point in the dataset, there are 4 independent variables : sepal_length, sepal_width, petal_length, petal_width. We try to find the class of each datapoint using these 4 variables, hence this dataset is Multivariate.

The species were categorical, hence I converted the nominal attributes into Ordinal where, 
'Iris-Setosa' : 1,
'Iris-Versicolor' : 2,
'Iris-Virginica' : 3

IDEA
I will be applying Gradient Descent algorithm to optimize the 5 parameters, including bias. The dataset was divided and shuffled into train and test and every time training data was made, gradient descent was called and an optimized parameter test data was tested and mean square error was given.

Observe the data 

<img width="305" alt="image" src="https://github.com/shreya-malraju/LinearRegression_Iris_dataset/assets/132793649/486090b0-2ef3-4d10-a07a-198f9b318d98">

Final values of theta, cost

<img width="419" alt="image" src="https://github.com/shreya-malraju/LinearRegression_Iris_dataset/assets/132793649/c5cd9455-8449-40f3-8484-2070b8bad7cf">

Mean square error after each iteration when the model is trained for each train data and tested on each test data

<img width="416" alt="image" src="https://github.com/shreya-malraju/LinearRegression_Iris_dataset/assets/132793649/06ce6650-85bd-47aa-bfea-161f5a9ff139">
