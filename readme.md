# 🎵 Music Genre Classification: Logistic Regression vs KNN

## 📌 Project Overview
This project focuses on comparing two machine learning classification algorithms — **Logistic Regression** and **K-Nearest Neighbors (KNN)** — for predicting music genres based on audio features.

The objective is to analyze model performance and understand the trade-offs between **accuracy, interpretability, and computational efficiency**.

---

## 📊 Project Information
 
- **Project Type:** Machine Learning Classification  
- **Domain:** Music Analytics  
- **Dataset Size:** 114,000 Songs  
- **Target Variable:** `track_genre`  
- **Number of Genres Used:** 10  
- **Models Compared:**
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  

- **Evaluation Metrics:**
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - Cross Validation Score  

---

## 🎧 Dataset
The dataset contains audio-based features such as:
- Energy
- Loudness
- Danceability
- Tempo
- Popularity

These features are used to classify songs into different genres.

---

## ⚙️ Models Used

### 1. Logistic Regression
- Linear classification algorithm  
- Fast and interpretable  
- Works best for linearly separable data  

### 2. K-Nearest Neighbors (KNN)
- Distance-based algorithm  
- Predicts based on nearest data points  
- Better for non-linear patterns  

---

## 🧪 Model Performance

| Model                | Accuracy / F1 Score | Cross-Validation Score |
|---------------------|---------------------|------------------------|
| Logistic Regression | 59.7%               | 59.2%                  |
| KNN Classifier      | 64.8%               | 60.1%                  |

---

## 📌 Key Insights

- KNN outperformed Logistic Regression in this dataset  
- The data contains **non-linear relationships**, which favor KNN  
- **Feature scaling was crucial** for KNN performance  
- Logistic Regression still provides strong interpretability and speed  

---

## ⚖️ Trade-offs

- **KNN**
  - ✔ Higher accuracy  
  - ❌ Slower predictions  
  - ❌ Memory intensive  

- **Logistic Regression**
  - ✔ Fast and efficient  
  - ✔ Easy to interpret  
  - ❌ Lower accuracy on complex patterns  

---

## 🎯 Final Conclusion

- **KNN is better for accuracy-focused applications**
- **Logistic Regression is better for speed, simplicity, and interpretability**

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas 📊  
- NumPy 🔢  
- Scikit-learn 🤖  
- Matplotlib / Seaborn 📈  

---

## 👨‍💻 Author
**Deep Jain**  
Machine Learning Enthusiast | Focused on AI/ML Development

**Linkedin**
https://www.linkedin.com/in/deep-jain-697071255
