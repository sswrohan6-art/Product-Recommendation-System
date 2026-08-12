# 🛍️ Product Recommendation System Using Sentiment Analysis

## Overview

A comprehensive machine learning solution that leverages sentiment analysis to deliver personalized product recommendations. This system combines collaborative filtering algorithms with sentiment-based scoring from customer reviews to improve recommendation accuracy and user satisfaction.

---

## 📚 Table of Contents

1. [🔍 Overview](#overview)
2. [📂 Project Structure](#-project-structure)
3. [✨ Features](#-features)
4. [💻 Key Technologies](#-key-technologies)
5. [📈 Model Performance](#-model-performance)
6. [⚙️ How to Run the Project](#️-how-to-run-the-project)
7. [🚀 Future Improvements](#-future-improvements)
8. [📬 Contact](#-contact)

---

## 📂 Project Structure

- **Sentiment Analysis**: Utilizes multiple ML classifiers to predict sentiment from product reviews.
- **Recommendation System**: Built using **user-based** and **item-based filtering** methods.
- **Sentiment Integration**: Combines sentiment scores with collaborative filtering for improved recommendations.

---

## ✨ Features

- **Text Preprocessing**: Used the **Natural Language Toolkit (NLTK)** for text cleaning and preparation.
- **Feature Extraction**: Extracted features using **TF-IDF** and **Word2Vec** from a dataset containing over **30,000 product reviews**.
- **Machine Learning Models**: Applied several classifiers for sentiment analysis:
  - Logistic Regression (LR)
  - Random Forest (RF)
  - XGBoost (XGB)
  - AdaBoost (AB)
  - K-Nearest Neighbors (KNN)
  - **Support Vector Machine (SVM)** emerged as the top performer, optimized with **5-fold cross-validation**.
- **Recommender System**:
  - Utilized **cosine similarity** for both user-user and item-item collaborative filtering.
  - Finalized **User-User collaborative filtering** with an **RMSE of 1.6**.
  - Integrated sentiment scores into the recommendation engine for better accuracy.

---

## 💻 Key Technologies

- **Python**: Core language for development.
- **NLTK**: For text preprocessing, including tokenization and stemming.
- **TF-IDF & Word2Vec**: Employed for feature extraction from text data.
- **scikit-learn, XGBoost**: Libraries used to train classifiers.
- **Cosine Similarity**: Distance metric used in collaborative filtering.
- **Collaborative Filtering**: Both user-based and item-based filtering approaches.

---

## 📈 Model Performance

- **Sentiment Analysis**: SVM showed superior performance over other classifiers.
- **Recommendation System**: The user-user based collaborative filtering model, enhanced with sentiment analysis, led to substantial improvement in recommendation accuracy.

---

## ⚙️ How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sswrohan6-art/Product-Recommendation-System.git
   cd Product-Recommendation-System
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the sentiment analysis and recommendation scripts**:
   ```bash
   python sentiment_analysis.py
   python recommendation_system.py
   ```

4. **Customize with your own data**:
   - Replace `data.csv` with your own dataset of product reviews for customized recommendations.

---

## 🚀 Future Improvements

- Add deep learning models to improve sentiment analysis accuracy.
- Explore hybrid recommendation methods by combining content-based and collaborative filtering.
- Optimize runtime for handling larger datasets efficiently.

---

## 📬 Contact & Contributing

For questions, suggestions, or contributions:
- GitHub: [@sswrohan6-art](https://github.com/sswrohan6-art)
- Feel free to fork this repository and submit pull requests

---

## 📄 License

This project is open source and available under the MIT License.

Happy recommending! 🌟
