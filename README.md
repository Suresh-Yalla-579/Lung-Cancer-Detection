# Lung-Cancer-Detection Research
## Introduction
Cancer, a condition characterized by the transformation of typically healthy cells into cancerous ones, ranks as the second leading cause of death in the United States. Within this spectrum of diseases, lung cancer emerges as the second most prevalent. In 2020, it accounted for 2.2 million deaths worldwide. Our research project focuses on developing an advanced ensemble model for the classification of lung diseases, particularly benign and malignant nodules.

## Dataset
We utilize the IQ-OTH/NCCD dataset, comprising images drawn from diverse demographics. This dataset includes 120 benign images, 561 malignant images, and 416 normal (healthy) images. The images encompass chest X-rays and computed tomography (CT) scan images.

## DenseNet Feature Extraction
DenseNet, or Dense Convolutional Network, is utilized for feature extraction. DenseNet's architecture promotes feature reuse and facilitates effective learning of intricate patterns within the data. We detail the internal procedures involved in feature extraction, including input processing, dense blocks, transition layers, global average pooling, and fully connected layers.

## XGBoost Ensemble Learning
XGBoost, or eXtreme Gradient Boosting, is employed for ensemble learning. It operates within the gradient boosting framework, sequentially training multiple weak learners (decision trees) to improve predictive accuracy. We explain the working procedure of XGBoost, including the objective function, prediction calculation, base learner training, gradient calculation, and tree construction.

## Ensemble Model
Our ensemble model combines the features extracted by DenseNet with the predictive power of XGBoost. The integration of XGBoost at the conclusion of the DenseNet architecture enhances our model's accuracy and efficiency. We elaborate on the advantages of this ensemble approach and its implications for medical image classification.

## Results and Conclusion
Our model demonstrates exceptional performance, excelling in accuracy and time efficiency for image classification. With a relatively small number of training epochs, our model achieves optimal accuracy and well-converged training and validation accuracy plots. Its rapid classification capabilities present promising prospects for practical applications in medical diagnosis.
