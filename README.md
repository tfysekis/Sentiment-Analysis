# Sentiment Analysis Model Comparison

This repository contains a detailed comparative analysis of various machine learning models for sentiment analysis. The project evaluates traditional machine learning models—Logistic Regression (LR) and Support Vector Machine (SVM)—alongside advanced deep learning models—Long Short-Term Memory (LSTM) networks and DistilBERT (a distilled version of BERT). The aim is to determine which model provides the best balance of accuracy, efficiency, and robustness for classifying sentiments in textual data.

## Models Evaluated

- **Logistic Regression (LR)**: A baseline machine learning model known for its simplicity and effectiveness in binary classification tasks.
- **Support Vector Machine (SVM)**: An advanced machine learning model that excels in handling high-dimensional data and complex model boundaries.
- **Long Short-Term Memory (LSTM)**: A type of recurrent neural network that is capable of learning order dependence in sequence prediction problems.
- **DistilBERT**: A transformer-based model that offers a good trade-off between performance and speed, suitable for tasks requiring understanding of context within text.

## Key Findings

- **SVM and LR Comparison**: SVM consistently outperformed LR, showing particular strengths in accurately classifying clear sentiment distinctions.
- **LSTM vs. CNN**: LSTM showed more stable and consistent performance across training epochs compared to CNN, which exhibited signs of overfitting.
- **LSTM vs. DistilBERT**: LSTM slightly outperformed DistilBERT in ROC curve analysis, especially in handling extreme sentiments effectively.

## Visualizations

Visual comparisons of model performance are provided through ROC curves, precision-recall curves, and learning curves. These visualizations help in understanding each model's strengths and weaknesses in the context of sentiment analysis.

## Conclusion

The comparative analysis suggests that while LSTM provides the best performance for complex sentiment analysis tasks requiring nuanced understanding of long text sequences, DistilBERT remains a strong contender for broader applications due to its efficiency and robust contextual understanding capabilities.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.
