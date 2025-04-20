# iris-knn-numpy
KNN implementation from scratch using NumPy on the Iris dataset, classifying Iris flowers based on Euclidean distance

# Iris Classification with KNN using NumPy

## Project Overview  
This project focuses on implementing the **K-Nearest Neighbors (KNN)** algorithm using only **NumPy** to classify Iris flowers.

The main goal is to compute **Euclidean distances** between training and test samples using three methods:
- Double loop method  
- Single loop method  
- Fully vectorized (no-loop) method

After calculating distances, we use `np.argpartition` to find the `k` nearest neighbors. Then, the **most frequent label** (mode) among these neighbors is assigned as the predicted class for each test sample.

Finally, we evaluate the model by comparing the predictions to the true labels and calculating the **accuracy**.

## Tasks Completed  
- Loaded and preprocessed the training and test datasets  
- Computed Euclidean distances using three different methods  
- Implemented KNN from scratch using only NumPy  
- Used mode to determine predicted labels  
- Calculated classification accuracy
