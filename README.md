# 🚢 Titanic Survival Prediction

## 📖 Overview
This project predicts passenger survival on the Titanic dataset using the **K-Nearest Neighbors (KNN)** algorithm.  
It demonstrates an end-to-end machine learning workflow including **data preprocessing, feature engineering, model training, evaluation, and visualization**.

---

## ⚙️ Workflow

### 1️⃣ Data Cleaning & Imputation
- Handled missing values using **SimpleImputer**  
  - `mean` strategy → Numerical column (`Age`)  
  - `most_frequent` strategy → Categorical columns (`Cabin`, `Embarked`)

### 2️⃣ Feature Engineering
- Applied **Label Encoding** for categorical features: `Name`, `Sex`, `Cabin`, `Embarked`, `Ticket`  
- Used **Standard Scaling** for numerical features  
- Performed **outlier treatment** using **Winsorization**

### 3️⃣ Model Training
- Trained a **KNeighborsClassifier** model with:
  - `n_neighbors = 9`  
- Selected features:
  - `Pclass`, `Sex`, `Age`

### 4️⃣ Model Evaluation
- Metrics:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report**
- Visualizations:
  - **Correlation Heatmap**
  - **Confusion Matrix Plot**

---

## 🛠️ Tech Stack
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn (KNN, Preprocessing, Metrics)  
- **Statistics**: SciPy (Winsorization)

---

## 📊 Results
- KNN model successfully classified survival cases  
- Achieved **reasonable accuracy** using selected features  
- Visual insights improved model interpretation

---

## 📈 Visualizations Included
- Boxplots  
- Correlation Heatmap  
- Confusion Matrix  

---

## 📌 Future Improvements
- Hyperparameter tuning (GridSearchCV)  
- Feature expansion (e.g., family size, fare bins)  
- Comparison with other classifiers (Logistic Regression, Random Forest, SVM)

---

## ✨ Author
Developed by **Dhanushya**  
Actively learning **AI & Data Science** with hands-on projects 🚀

---

## 🚀 Conclusion
This project demonstrates how **K-Nearest Neighbors (KNN)** can be effectively used for classification tasks with proper **preprocessing, scaling, and feature selection**.

---

## 📂 Repository Structure
