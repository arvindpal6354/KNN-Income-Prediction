# KNN-Income-Prediction
🎓 IBM SkillBuild AI/ML Internship Project

This project was developed as part of the **IBM SkillBuild AI/ML Internship**.  
It uses the UCI Adult Census Dataset to predict whether a person earns more than \$50K per year based on their demographic attributes using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 🔍 Problem Statement

The goal is to build a binary classification model to determine if an individual earns more than \$50K annually.  
The prediction is based on demographic and employment-related features such as:

- Age
- Education level
- Hours worked per week
- Marital status
- Occupation
- Capital gain/loss

---

## 🛠 Technologies Used

- 🐍 Python (Google Colab)
- 🧮 Pandas, NumPy
- 🤖 Scikit-learn (KNN model)
- 📊 Matplotlib, Seaborn

---

## 📊 Project Workflow

1. Upload dataset (`adult 3.csv`)
2. Handle missing data
3. Encode categorical variables using LabelEncoder
4. Train-test split (80/20)
5. Train K-Nearest Neighbors (KNN) model
6. Evaluate accuracy and classification metrics
7. Visualize:
   - Confusion Matrix
   - Accuracy vs K Value plot

---

## ✅ Results

- 📈 **Model Accuracy:** ~83%
- 📊 Visual evaluation using confusion matrix and classification report
- 🔁 Accuracy tuned by trying different K values (1–20)

---

## 📸 Screenshots

### 1. Uploading Dataset and Preview  
![Upload](https://github.com/arvindpal6354/KNN-Income-Prediction/blob/main/screenshots/Screenshot%202025-07-19%20104035.png?raw=true)

### 2. After Label Encoding  
![Encoded Data](https://github.com/arvindpal6354/KNN-Income-Prediction/blob/main/screenshots/Screenshot%202025-07-19%20104113.png?raw=true)

### 3. Model Accuracy and Report  
![Accuracy Report](https://github.com/arvindpal6354/KNN-Income-Prediction/blob/main/screenshots/Screenshot%202025-07-19%20104248.png?raw=true)

### 4. Confusion Matrix  
![Confusion Matrix](https://github.com/arvindpal6354/KNN-Income-Prediction/blob/main/screenshots/Screenshot%202025-07-19%20104307.png?raw=true)

### 5. Accuracy vs K Value Plot  
![K Accuracy Plot](https://github.com/arvindpal6354/KNN-Income-Prediction/blob/main/screenshots/Screenshot%202025-07-19%20104327.png?raw=true)


---

## 📈 Future Scope

- 🔗 Deploy model as a Streamlit web app
- 📏 Improve accuracy by applying feature scaling (StandardScaler)
- ⚖️ Try different ML algorithms (Logistic Regression, SVM, Random Forest)
- 🔍 Perform hyperparameter tuning using GridSearchCV

---

## 📂 Files in this Repository

| File | Description |
|------|-------------|
| `knn_income_classifier.ipynb` | Main Google Colab notebook |
| `adult 3.csv` | Dataset used (UCI Adult Census) |
| `requirements.txt` | Libraries used |
| `README.md` | Project documentation (this file) |

---

## 👨‍💻 Developed By

**Rushikesh Patil**  
💼 Internship: IBM SkillBuild AI/ML  
📅 Internship Period: 6 Week 
📫 GitHub: arvindpal6354 (https://github.com/arvindpal6354)

---

> ⭐ If you found this useful or interesting, don't forget to star the repo!



---

🧠 **Developed during:** IBM SkillBuild AI/ML Internship  


