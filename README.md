# Classification of Breast Cancer Histopathological Images Using Machine Learning

In this project, different machine learning techniques and deep learning models are used to classify breast cancer histopathological images into its corresponding classes.
Breast cancer tumors are divided into two main groups: benign tumors and malignant tumors.
The dataset used is BreakHis. (https://www.kaggle.com/datasets/akshathraj/breakhis-40x/).
The dataset currently contains four histological distinct types of benign breast tumors: adenosis (A), fibroadenoma (F), phyllodes tumor (PT), and tubular adenona (TA);  and four malignant tumors (breast cancer): carcinoma (DC), lobular carcinoma (LC), mucinous carcinoma (MC) and papillary carcinoma (PC).
It is highly imbalanced dataset so I've used resampling techniques like SMOTE and Tomek Links elimination for balancing.
Then I've used deep learning models like CNN, VGG-19 and DenseNet-121 for classification.
Then I've ensembled the predictions of different models for better accuracy.
Implementation can be seen in the notebook file.
