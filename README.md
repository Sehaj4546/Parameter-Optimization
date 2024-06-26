# Parameter-Optimization
## By : Sehajbir Singh Bains (102103290)

## SVM Optimization on Dataset

This project demonstrates the optimization of Support Vector Machine (SVM) on the Dry Bean dataset obtained from the UCI Machine Learning Repository. The dataset contains instances of seven different varieties of dry beans, with 16 features describing each instance.

## Dataset

The Dry Bean dataset consists of 13611 instances, with each instance having 16 features. The dataset is divided into 10 different samples for training and testing.

## Implementation

1. **Loading the Dataset**: The dataset is loaded from a CSV file using the pandas library.

2. **Splitting the Dataset**: The dataset is split into training and testing sets with a 70-30 ratio, repeated 10 times to get 10 different samples.

3. **Optimizing SVM**: SVM is optimized for each sample using cross-validation with 100 iterations. GridSearchCV is used to find the best hyperparameters.

4. **Recording Results**: The best parameters and accuracies are recorded for each sample. The sample with maximum accuracy is identified.

![notfound](https://github.com/Sehaj4546/Parameter-Optimization/blob/787c9492d71b63cc2205736f2edf784b1eb48c04/table.png)


5. **Convergence Graph**: A convergence graph is plotted for the sample with the maximum accuracy, showing how the training and testing accuracies change over iterations during the optimization process.

![notfound](https://github.com/Sehaj4546/Parameter-Optimization/blob/787c9492d71b63cc2205736f2edf784b1eb48c04/result_graph.png)

## Acknowledgments

- UCI Machine Learning Repository for providing the Dry Bean dataset.
- Scikit-learn and pandas libraries for their functionalities in data preprocessing and machine learning.
