
# 🎬 Movie Recommendation System using Apache Spark

This project is a **movie recommendation system** built using **Apache Spark** and trained on the **MovieLens-1M** dataset accessed via the `tensorflow-datasets` library. It uses the **ALS (Alternating Least Squares)** algorithm to provide personalized movie recommendations for users based on collaborative filtering.

---

## 🚀 Project Overview

This recommendation system aims to predict a user's movie preferences by analyzing their past ratings and identifying similar user behaviors. The model is trained using Spark's MLlib and efficiently handles large-scale data processing using Apache Spark.

---

## 📊 Dataset

- **Dataset**: [MovieLens 1M](https://grouplens.org/datasets/movielens/1m/)
- **Source**: Accessed through the `tensorflow-datasets` library.
- **Contents**:
  - 1 million ratings from 6,000 users on 4,000 movies.
  - User demographics (age, gender, occupation, zip).
  - Movie metadata (title, genres).

---

## 🧠 Algorithm

- **Model Used**: ALS (Alternating Least Squares)
- **Library**: Apache Spark MLlib
- **Why ALS?**:
  - Efficient for collaborative filtering with implicit/explicit feedback.
  - Scales well with large datasets.

---

## 🛠️ Technologies Used

- **Apache Spark** (PySpark)
- **TensorFlow Datasets**
- **Python**
- **Google Colab**

---

## 🔧 How It Works

1. **Load Dataset**: The MovieLens-1M dataset is loaded using the `tensorflow_datasets` library and preprocessed to extract `userId`, `movieId`, and `rating`.
2. **Data Transformation**: Data is converted into a Spark DataFrame compatible with the ALS model format.
3. **Model Training**: The ALS model is trained on the user-movie-rating matrix.
4. **Evaluation**: The model is evaluated using RMSE (Root Mean Squared Error).
5. **Recommendations**: For each user, top-N movie recommendations are generated.

---

## 📌 Features

- Generate top-N movie recommendations for each user.
- Handle large-scale data using Apache Spark.
- Easy to extend for genre-based or hybrid recommendations.

---

## 📦 Installation & Usage

1. Clone the repository:

2. Set up environment and install dependencies:

3. Run the notebook:

   Open `Movie_Recommendation_System.ipynb` in Jupyter or Colab and run.

---
