# Vietnamese Text Classification and Sentiment Analysis

This repository is dedicated to solving the problems of **text classification** and **sentiment analysis** for Vietnamese text. The project leverages both traditional machine learning methods and modern deep learning techniques to process and analyze text data effectively.

---

## Overview

### Objectives
- Perform **text classification** to categorize text into specific topics.
- Conduct **sentiment analysis** to determine the sentiment (e.g., positive, neutral, negative) of text.

### Methodologies
The project workflow consists of the following steps:
1. **Preprocessing:** Cleaning and preparing text data for analysis.
2. **Feature Extraction:** Using methods like Bag of Words (BoW) and TF-IDF for traditional approaches.
3. **Modeling:**
   - Traditional: Naïve Bayes, KNN, SVM, Decision Trees, Random Forest.
   - Deep Learning: RNN, LSTM, CNN, Transformer, and GCN models.
4. **Evaluation:** Models are evaluated using metrics like Accuracy, F1-Score, and Micro-F1.

---

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)

## Features
- **Text Preprocessing**: Tokenization and cleaning tailored for Vietnamese language specifics.
- **Machine Learning Models**: Implementation of algorithms such as Naïve Bayes, Logistic Regression, Support Vector Machines (SVM), and deep learning approaches using neural networks.
- **Performance Evaluation**: Metrics like accuracy, precision, recall, and F1-score are calculated to compare models.
- **Visualization**: Displays model performance through charts and graphs for better analysis.

## Prerequisites
Before running the project, ensure you have the following:

- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries:
  - numpy
  - pandas
  - scikit-learn
  - tensorflow/keras
  - matplotlib
  - underthesea (for Vietnamese text tokenization and processing)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thanghd1112/VNTextClassify-Sentiment.git
   cd Vietnamese-Text-Classification
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

### Name
**Synthetic Vietnamese Students’ Feedback Corpus**

### Description
This dataset contains synthetic feedback from Vietnamese students. It is structured to support both text classification and sentiment analysis tasks.

### Source
The dataset can be accessed on Kaggle: [Synthetic Vietnamese Students’ Feedback Corpus](https://www.kaggle.com/datasets/toreleon/synthetic-vietnamese-students-feedback-corpus/data).

### Key Features
- **Language:** Vietnamese
- **Usage:** Designed for tasks like topic categorization and sentiment detection.
- **Structure:** Includes text samples with corresponding labels (sentiment/topic).

---

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook VNTextClassify-Sentiment.ipynb
   ```
2. Run the cells sequentially to preprocess the data, train the models, and evaluate their performance.
3. Modify the parameters or add additional models as needed.

## Project Workflow

1. **Data Preprocessing**:
   - Tokenization using `underthesea`
   - Removal of stopwords, punctuation, and normalization

2. **Model Training**:
   - Train machine learning models like Naïve Bayes, Logistic Regression, and SVM
   - Experiment with deep learning models (e.g., LSTM, GRU)

3. **Evaluation**:
   - Evaluate models using metrics such as accuracy, precision, recall, and F1-score

4. **Visualization**:
   - Visualize performance metrics for better understanding and comparison

## Results
- The notebook provides detailed insights into model performance.
- A summary table compares all models to identify the best-performing one for Vietnamese text classification.

## Future Work
- Enhance preprocessing with additional Vietnamese-specific features.
- Experiment with transformer-based models like BERT for Vietnamese.
- Expand the dataset for more comprehensive evaluation.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

For further discussions or queries, connect with me on [LinkedIn](https://www.linkedin.com/in/thang-hoang-3b6954295).

---
Thank you for reading!
