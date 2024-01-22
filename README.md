Overview: 



This project is centered around detecting fraudulent credit card transactions using machine learning models. We employ Decision Tree and Support Vector Machine (SVM) models implemented through the Scikit-Learn and Snap ML Python APIs, with a particular emphasis on the use of Snap ML. Snap ML stands out as a high-performance machine learning library from IBM, renowned for its efficient CPU/GPU implementations of linear and tree-based models. It excels in accelerating ML algorithms, not just through system awareness but also by offering state-of-the-art ML algorithms with superior accuracy.

Dataset:



The dataset, sourced from Kaggle ([Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)), comprises credit card transactions made by European cardholders in September 2013. This dataset is notably unbalanced, containing only 492 fraudulent transactions out of 284,807 total transactions. Such imbalance poses a unique challenge in model training and evaluation, necessitating careful consideration of the minority class during the model development process.

Approach:



In this project, we tackle the issue using binary classification, where '1' indicates a positive class (fraudulent transaction) and '0' represents a non-fraudulent transaction. To address the significant class imbalance in the dataset, we adopt strategies that bias the models to pay more attention to samples in the minority (fraudulent) class. This is achieved by configuring the models to consider class weights during the training/fitting process, ensuring a more balanced focus on both classes.

Objectives:



The primary objective of this project is to effectively identify fraudulent transactions using advanced ML techniques while tackling the challenges posed by an unbalanced dataset. By comparing the performance of Decision Trees and SVMs in both Scikit-Learn and Snap ML frameworks, we aim to highlight the strengths and limitations of each approach in handling such complex, real-world datasets.


