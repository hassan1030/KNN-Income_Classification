# Income Classification Using k-Nearest Neighbors (k-NN)

## Introduction
In this project, I implemented a k-Nearest Neighbors (k-NN) model to classify individuals based on income levels (≤50K or >50K) using demographic and occupational attributes. The goal was to explore the relationships between various features and income, build a predictive model, and evaluate its performance.

## Analysis
I began by preprocessing the dataset, handling missing values, and normalizing numerical features. Categorical variables were encoded to ensure compatibility with the k-NN algorithm. I conducted exploratory data analysis (EDA) to understand the data better, including generating a correlation heatmap and visualizations of categorical variables against income levels.

The k-NN model was then trained and evaluated by testing different values of \( k \) to identify the optimal number of neighbors. I used accuracy metrics, a classification report, and a confusion matrix to assess the model's performance.

## Results and Conclusion
The k-NN model achieved an accuracy of **82.76%**, with \( k = 13 \) being the optimal value. The model performed well in predicting individuals with income ≤50K but showed lower recall for the >50K category. This suggests room for improvement, such as addressing class imbalance or exploring advanced algorithms.

Overall, this project provided valuable insights into feature importance and highlighted the utility of k-NN for classification tasks in income prediction.

## Repository Contents
- **Report**: A detailed word document summarizing the analysis, visualizations, and results.
- **Python Code**: The Python script for preprocessing, EDA, and k-NN implementation.
- **Visualizations**:
  - Classification Report Screenshot
  - Accuracy vs. K Value Graph
