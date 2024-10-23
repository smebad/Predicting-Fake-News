# 📰 Fake News Prediction Project 🕵️‍♂️

Welcome to the **Fake News Prediction Project**! This project uses machine learning to detect and classify fake news articles. We leverage the power of **Logistic Regression** to identify whether a news article is **real** or **fake** based on its content.

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [🗂 Dataset](#dataset)
- [🔧 Installation](#installation)
- [🚀 Usage](#usage)
- [📊 Results](#results)
- [💻 Technologies Used](#technologies-used)

---

## Project Overview
In this project, we aim to:
- 🧠 Build a machine learning model that can classify news articles.
- 📉 Evaluate the model's performance using accuracy metrics.
- 📝 Gain insights into fake news through data analysis.

The core model used is **Logistic Regression**, which helps us predict whether a news article is fake or not based on its title, author, and content.

---

## 🗂 Dataset
The dataset used is from the [Fake News Challenge](https://www.kaggle.com/c/fake-news/data) on Kaggle, containing labeled news articles. Here’s a quick overview:

- **id**: Unique identifier for each news article.
- **title**: The title of the news article.
- **author**: The author of the news article.
- **text**: The body content of the news article.
- **label**: 1 = Fake, 0 = Real.

---

## 🔧 Installation
Follow these steps to get the project up and running on your local machine:

1. **Clone** the repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-prediction.git
   ```
## 🚀 Usage
* Load the project in Jupyter Notebook by opening fake_news_prediction.ipynb.
* Make sure the dataset files (train.csv and test.csv) are in the correct directory.
* Execute the cells step by step to train the model and make predictions.

## 📊 Results
Our Logistic Regression model achieves an accuracy of 90+ % on the test data. The model can be improved by using techniques such as TF-IDF Vectorization or other advanced NLP techniques.

## 💻 Technologies Used
* Python 🐍
* Pandas for data manipulation.
* Scikit-learn for model building.
* Jupyter Notebook for running and documenting code.

## ⭐ If you like this project, don’t forget to give it a star on GitHub! ⭐
