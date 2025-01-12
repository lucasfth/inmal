# Exam

## Outline for Presentation on Metrics, Evaluation, and Cross-Validation

1. Introduction (30 seconds)
    * Provide an overview of the importance of evaluation metrics and data considerations in ML.
    * Highlight the focus areas:
        * (a) Metrics/Evaluation of classifiers.
        * (b) Metrics/Evaluation of regression.
        * (c) Imbalanced data in classification and regression.
        * (d) Cross-validation.
        * (e) Matching and metrics.
2. Metrics and Evaluation for Classifiers (1 minute)
    * Key Metrics:
        * Accuracy, precision, recall, F1-score, ROC-AUC.
    * Insights:
        * Explain how each metric provides a different perspective on classifier performance.
    * Examples:
        * Use 02-metrics.ipynb to demonstrate classifier evaluation metrics and their practical interpretation.
3. Metrics and Evaluation for Regression (1 minute)
    * Key Metrics:
        * Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), R².
    * Insights:
        * Discuss when each metric is most applicable and what it reveals about model performance.
    * Examples:
        * Refer to regression examples in 03-basis.ipynb to illustrate these metrics.
4. Handling Imbalanced Data (1 minute)
    * Challenges in Classification:
        * Explain how class imbalance skews metrics like accuracy.
        * Introduce methods like re-sampling, SMOTE, and adjusting decision thresholds.
    * Challenges in Regression:
        * Highlight the issue of unevenly distributed target variables and its impact on models.
    * Examples:
        * Refer to relevant portions of 02-metrics.ipynb or 04-hog_classifier.ipynb for practical examples.
5. Cross-Validation (1 minute)
    * Purpose:
        * Explain cross-validation as a technique to assess model generalizability and reduce overfitting.
    * Techniques:
        * Discuss k-fold, stratified k-fold, and leave-one-out cross-validation.
    * Examples:
        * Use 01-nonlineardecision.ipynb to demonstrate cross-validation in practice.
6. Matching and Metrics (1 minute)
    * Matching:
        * Explain the concept of matching in the context of classification or feature extraction (e.g., HOG matching).
    * Metrics for Matching:
        * Introduce precision-recall metrics or distance-based evaluations (e.g., Euclidean distance).
    * Examples:
        * Refer to 04-hog_classifier.ipynb to showcase how matching metrics are applied.
7. Conclusion (30 seconds)
    * Recap the importance of evaluation metrics for classifiers and regression models.
    * Emphasize the need for robust handling of imbalanced data and cross-validation to improve model performance.
    * Highlight how matching and metrics are integral for certain ML applications like object detection.