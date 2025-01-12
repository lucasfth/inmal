# Exam

## Outline for Presentation on Neural Networks

1. Introduction (30 seconds)
    * Introduce neural networks and their versatility in solving regression and classification tasks.
    * Highlight the focus areas:
        * Prediction, training, evaluation, model architectures, loss functions, regularization, and bias-variance.
2. Neural Networks: Prediction (Regression vs. Classification) (1 minute)
    * Regression vs. Classification:
        * Regression: Outputs continuous values (e.g., house prices).
        * Classification: Outputs discrete labels (e.g., cat vs. dog).
    * Activation Functions:
        * Discuss the role of activations (e.g., sigmoid for binary classification, ReLU for regression).
    * Examples:
        * Use 03-activation_loss.ipynb or 07-nn-gaze.ipynb to showcase prediction tasks for both regression and classification.
3. Neural Networks: Training (1.5 minutes)
    * Forward and Backward Propagation:
        * Explain the role of gradients and the chain rule in updating weights.
    * Optimization:
        * Discuss gradient descent and its variants (e.g., SGD, Adam) as seen in 01-optimization.ipynb.
    * Practical Demonstrations:
        * Walk through examples of forward and backward propagation in 02-nn.ipynb.
4. Training and Evaluation (1 minute)
    * Overfitting and Underfitting:
        * Define and identify these issues using training/validation curves.
    * Evaluation:
        * Discuss performance metrics like accuracy, RMSE, and F1-score.
        * Highlight examples from 03-bias_variance.ipynb that illustrate evaluation techniques.
5. Model Architectures (1.5 minutes)
    * Fully Connected/MLP vs. CNN:
        * MLP: Dense layers for general-purpose tasks.
        * CNN: Convolutional layers for spatial data like images.
    * Key Differences:
        * Discuss parameter sharing in CNNs vs. dense connections in MLPs.
    * Examples:
        * Use 02-nn.ipynb to compare architectures and their applications.
6. Loss Functions, Regularization, and Model Complexity (1.5 minutes)
    * Loss Functions:
        * Explain common losses (MSE for regression, cross-entropy for classification).
    * Regularization:
        * L1/L2 penalties, dropout, and their role in preventing overfitting.
    * Data Augmentation:
        * Briefly discuss techniques to enhance training datasets.
    * Cross-Validation:
        * Highlight its use in model evaluation and hyperparameter tuning.
    * Examples:
        * Use 03-activation_loss.ipynb to showcase loss function usage and regularization effects.
7. Regularization, Cross-Validation, and Bias-Variance (1.5 minutes)
    * Bias-Variance Tradeoff:
        * Define and demonstrate its impact on model performance.
    * Regularization and Cross-Validation:
        * Explain how they mitigate overfitting and improve generalization.
    * Examples:
        * Use 03-bias_variance.ipynb to illustrate these concepts with visualizations and practical applications.
8. Conclusion (30 seconds)
    * Recap the key takeaways:
        * Neural networks handle diverse tasks through flexible architectures and training methods.
        * Regularization and cross-validation are crucial for mitigating overfitting and ensuring generalization.
        * Bias-variance tradeoff is central to understanding model complexity and performance.
