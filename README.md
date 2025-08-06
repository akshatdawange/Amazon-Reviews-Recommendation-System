
# 📦 Amazon Reviews Recommendation System

This project builds a **Recommender System** using Amazon product review data. The goal is to predict user ratings for unseen products, enabling personalized recommendations using a variety of collaborative filtering algorithms.

Developed as part of the **FIT5212: Data Analysis for Semi-Structured Data** course at Monash University.

## 🔍 Project Objective

To implement and evaluate multiple recommendation algorithms on real-world Amazon product reviews and generate accurate rating predictions for user–product pairs.

---

## 🧠 Models Implemented

- **SVD (Singular Value Decomposition)** – via `scikit-surprise`
- **KNNBasic** – User and Item-based collaborative filtering
- **NMF (Non-negative Matrix Factorization)**
- **NCF (Neural Collaborative Filtering)**

---

## 📊 Exploratory Data Analysis

- Distribution of user ratings
- Sparsity calculation of the user-item matrix
- Visual insights into dataset characteristics

---

## 📁 Data

- `train.csv`: Contains user-item-rating triplets used to train models
- `test.csv`: Contains user-item pairs for which predictions are generated

---

## 🧪 Evaluation Metric

- **Root Mean Squared Error (RMSE)** is used to evaluate model performance.
- Cross-validation is applied where appropriate.

---

## 🛠️ Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-surprise` for collaborative filtering models
- `scikit-learn` for preprocessing and metrics
- `lightgbm` for tree-based regression
- `torch` for deep learning model

---

## ⚙️ Setup Instructions

```bash
# Create a fresh environment (optional)
python -m venv recommender-env
source recommender-env/bin/activate  # On Windows use recommender-env\Scripts\activate

# Install dependencies
pip uninstall numpy
pip install numpy==1.24.4
pip install scikit-surprise
pip install torch
pip install lightgbm
pip install pandas matplotlib seaborn scikit-learn
```

---

## 🧩 File Structure

```
.
├── Amazon-Reviews-Recommendation-System.ipynb  # Main Jupyter notebook
├── train.csv                                    # Training dataset
├── test.csv                                     # Test dataset
└── README.md                                    # Documentation
```

---

## 📌 Highlights

- 📈 Multiple models compared on consistent metrics
- 🧠 Neural network recommender implemented from scratch
- 🧪 Experimental tuning with `GridSearchCV`
- 🎯 Focus on real-world recommender challenges: sparsity, scalability, and cold start

---

## 👤 Author

**Akshat Dawange**  
📍 Melbourne, Australia  
📧 [akshat.dawange21@gmail.com](mailto:akshat.dawange21@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/akshat-dawange-871959209/) | [GitHub](https://github.com/akshatdawange)
