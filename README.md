# irisflower_project
This program applies basic machine learning (classification) concepts on *Fisher's Iris Data* to predict the species of a new sample of Iris flower.
**Software and Libraries**
- Python 3.7.10
- scikit-learn 0.18.1
**Introduction**  
The dataset for this project originates from the Kggle platform The Iris flower data set or Fisher's Iris data set is a multivariate data set. The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.
- The data set consists Arround 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
- Four features were measured from each sample (in centimetres): 
  - Length of the sepals
  - Width of the sepals
  - Length of the petals
  - Width of the petals

**Working of the iris_decision_tree_classifier**
- The program takes data from the `load_iris()` function available in `sklearn` module.
- The program then creates a decision tree based on the dataset for classification.
- The user is then asked to enter the four parameters of his sample and prediction about the species of the flower is printed to the user.

**Working of the iris_selfmade_KNN**
- The program takes data from the `load_iris()` function available in `sklearn` module.
- The program then divides the dataset into training and testing samples in 80:20 ratio randomly using `train_test_learn()` function available in `sklearn` module.
- The training sample space is used to train the program and predictions are made on the testing sample space.
- Accuracy score is then calculated by comparing with the correct results of the training dataset.
