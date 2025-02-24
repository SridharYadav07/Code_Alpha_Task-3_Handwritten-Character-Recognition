# Code_Alpha_Task-3_Handwritten-Character-Recognition

This is a complete end-to-end implementation of a handwritten letter recognition system. It uses a Convolutional Neural Network for image classification based on a dataset of handwritten alphabet letters.
The dataset includes 28*28 grayscale images of letters, and the goal is to train a deep learning model to recognize these letters.
Here is an overview of the steps followed in the code.

Matplotlib for data visualization
Pandas and NumPy for handling and manipulating data
Scikit-learn for data splitting and shuffling

Data Preparatio: 
The features (x) are separated from the target labels (y).
The data is split into training and testing sets using train_test_split (80% training and 20% testing).
The data is reshaped to 28*28 pixles, which is the input format expected by CNN models.
The target labels are encoded as integers and then converted to one-hot encoding.

Data Visualization:
A bar plot is generated to visualize the distribution of the letters in the dataset, showing the frequency of each letter.
A few random images are shuffled and displayed to verify the dataset visually.

Data Reshaping:
The input data is reshaped to include a single channel by adding a dimension to the data using .reshape().

