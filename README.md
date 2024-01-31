# stellar-classification-ml

The notebook presents an exploratory analysis of the data from the "star_classification.csv" dataset, which contains information on 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). The observations are described by 17 feature columns and 1 class column that identifies the observation as a star, galaxy, or quasar.

The exploratory analysis showed that the class distribution is quite uneven, with 59,445 observations classified as galaxies, 21,594 as stars, and 18,961 as quasars. It was also observed that the data features are normally distributed and there are no missing values.

After standardizing the features, the data was split into training and test sets with 80% and 20% of the observations, respectively.

Three machine learning models were tested for classification of the observations: decision tree, K-Nearest Neighbors (KNN), and Support Vector Machines (SVMs).

The decision tree model achieved the best accuracy on the test set, with 97.36%. The KNN model achieved the second-best accuracy, with 90.09%. The SVM model achieved the third-best accuracy, with 96.04%. 

The following table summarizes the results of the models:

<table>
  <tr><td>Model</td><td>Accuracy on test set</td></tr>
  <tr>Decision tree</tr><tr>97.36%</tr>
  <tr>K-Nearest Neighbors (KNN)</tr><tr>90.09%</tr>
  <tr>Support Vector Machines (SVMs)</tr><tr>96.04%</tr>
</table>

# Comments

The results of the analysis show that all three machine learning models are capable of classifying the observations from the dataset with high accuracy. The decision tree model achieved the best accuracy, followed by the KNN model and the SVM model.

It is important to note that the results may vary depending on the parameters of the models and the splitting of the data into training and test sets. Additionally, it is important to consider the context of the problem when choosing the best model.

# Recommendations

Based on the results presented, it is recommended to use the decision tree model for classifying the observations from the dataset. This model achieved the best accuracy on the test set and is relatively simple to interpret.
