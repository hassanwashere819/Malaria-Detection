# Malaria-Detection
Image classification pipeline for detecting malaria-infected blood cells using VGG16 feature extraction, SMOTE, and traditional machine learning classifiers.
The project focuses on classifying microscopic blood-cell images into malaria-infected and non-infected categories. A transfer-learning approach was used with the pretrained VGG16 model to extract image features. Image augmentation was applied to increase the effective training data and improve model generalization.

Because of class imbalance in the extracted feature data, SMOTE (Synthetic Minority Over-sampling Technique) was applied before training the classification models. Three machine learning classifiers—Logistic Regression, Random Forest, and Decision Tree—were then trained and compared.

Model performance was evaluated using Stratified 5-Fold Cross-Validation, with Accuracy, Precision, Recall, and F1-score used as evaluation metrics.
