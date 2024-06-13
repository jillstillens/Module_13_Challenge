# Module_13_Challenge - Rubric

## Prepare the Data for Use on a Neural Network Model (20 points)

To receive all points, you must
+ Read the data into a DataFrame and drop the columns that are not relevant. (5 points)
+ Encode the categorical variables using OneHotEncoder, and place the encoded variables in a new DataFrame. (5 points)
+ Create the features (X) and target (y) datasets, and split them into training and testing datasets. (5 points)
+ Use scikit-learn's StandardScaler to scale the features data. (5 points)

## Compile and Evaluate a Binary Classification Model Using a Neural Network (25 points)

To receive all points, you must
+ Create a deep neural network by assigning the number of input features, the number of layers, and the number of neurons on each layer using Tensorflow’s Keras. (5 points)
+ Compile and fit the neural network model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric. (5 points)
+ Evaluate the model using the test data to determine the model’s loss and accuracy. (10 points)
+ Save and export the model to an HDF5 file, and name the file AlphabetSoup.h5. (5 points)

## Optimize the Neural Network Model (25 points)

To receive all points, you must
+ Define at least two deep neural network models (the original model, plus two optimisation attempts). Try to improve on your first model’s predictive accuracy. (10 points)
+ Display the accuracy scores achieved by each model, and compare the results. (10 points)
+ Save each model as an HDF5 file. (5 points)

## NOTE
You will not lose points if your model does not achieve high accuracy, as long as you make at least two attempts to optimize the model.

## Coding Conventions and Formatting (10 points)

To receive all points, you must
+ Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants. (3 points)
+ Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
+ Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
+ Use concise logic and creative engineering where possible. (2 points)

## Deployment and Submission (10 points)

To receive all points, you must
+ Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (5 points)
+ Include appropriate commit messages in your files. (5 points)

## Code Comments (10 points)

To receive all points, your code must
+ Be well commented with concise, relevant notes that other developers can understand. (10 points)
