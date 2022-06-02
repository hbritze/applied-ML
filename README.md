# Machine Learning Final Exam 2021/2022

***
This file contains information and details about how to run the "ML_Exam_2021_code.ipynb".
The code is written to supply the solutions to the tasks in question 3 "Variable Stars" of the Machine Learning 2020-2021 Exam.
***


TABLE OF CONTENTS 

-----------------

* General information

* Technologies

* How to run


GENERAL INFORMATION

-------------------

The code of the notebook "ML_Exam_2021_code.ipynb" is structured into the sub-questions 3.1-3.4.
 
* 3.1 - Data understanding and preprocessing: this section prints the class counts and class frequencies for the train and test set, respectively. It prints the classes with 65 or more training examples, the shape of the reduced train and test set, and the mean and variance of the normalized train and test set.

* 3.2 - Principal component analysis: this section performs PCA on the preprocessed and normalized training data, prints an eigenspectrum, projects the training data on the first two principal components (PCs), prints the dimension of the projected training data, and plots the projected training data colored according to the star class.  

* 3.3 - Clustering: this section performs 4-means clustering on the preprocessed and normalized training data, prints the predicted cluster labels, prints the dimension of the four obtained cluster centroids, prints the coordinates of the four cluster centroids projected on the first two PCs, prints the same scatter plot as in 3.2 but with the cluster centroids visualized. 

* 3.4 - Classification: consists of three classification tasks.

1. Multi-nomial logistic regression with one-norm regularization printing train and test loss, without regularization printing train and test loss, with two-norm regularization printing train and test loss, perform a grid-search and prints the tuned hyperparameters, prints the train and test loss for the model with the tuned hyperparameters. 

2. Random forest with 200 trees and square root of total features on preprocessed training data, perform a grid-search to tune additional hyperparameters, prints the tuned parameters, prints the OOB error, prints the train and test loss.
Random forest with 200 tress and total number of features and perform a grid-search, prints the tuned parameters, print the OOB error, prints the train and test loss. 

3. K-nearest neighbor classification using 5-fold cross-validation to determine the best value of K, prints the obtained best value for K, prints the train and test loss.


TECHNOLOGIES

------------

* Python: Version 3.7.4

* numpy library: Version 1.19.1

* pandas library: Version 1.1.1

* matplotlib library: Version 3.2.2

* scikit-learn library: Version 0.23.2


HOW TO RUN

----------

Open the file "ML_Exam_2021_code.ipynb in Jupyter Notebook to run the code or execute it from the terminal. 
It is recommended to run the code in Jupiter Notebook for better overview of what results belong to which sub-questions. Furthermore, markdown comments are made in between the code cells, explaining what the code is used for. 
The code calls the two data files "VSTrain.dt" and "VSTest.dt", which are included in the .zip file "ML_Exam2021_code.zip", where the notebook is also located.  
