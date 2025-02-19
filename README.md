🌲 Random Forest Classifier for Sentiment Analysis

🚀 Overview

This project implements a Random Forest Classifier to analyze sentiment from text data. Using bagging (Bootstrap Aggregating) and Decision Trees (ID3 Algorithm), the model enhances prediction accuracy through ensemble learning.

🎯 Features

Random Forest with Bagging: Uses multiple decision trees to improve predictions.

Feature Subset Selection: Randomly selects a subset of features at each split for better generalization.

Sparse Vector Processing: Efficiently handles large datasets.

Learning Curve Analysis: Tracks model performance as training data increases.

Evaluation Metrics: Computes precision, recall, and F1-score.

📁 Project Structure

├── RandomForest/

│   ├── DataParser.java            # Reads vectors, labels, and features from files

│   ├── ID3.java                   # Implements the ID3 Decision Tree Algorithm

│   ├── LearningCurveGenerator.java # Generates learning curves

│   ├── Main.java                   # Main execution file for training & evaluation

│   ├── Node.java                   # Represents a decision tree node

│   ├── Pair.java                   # Utility class for feature-value pairs

│   ├── RandomForest.java           # Implements the Random Forest Classifier

├── Utils/

│   ├── EvaluationMetrics.java       # Computes precision, recall, and F1-score


🔬 How It Works

Train the Model: Builds multiple decision trees using randomly selected features.

Predict Sentiment: Aggregates predictions from all trees to classify new text.

Evaluate Performance: Computes precision, recall, and F1-score.

Generate Learning Curve: Analyzes model accuracy across different training sizes.
