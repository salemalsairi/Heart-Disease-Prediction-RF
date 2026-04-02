# 🩺 Heart Disease Prediction (AI Doctor)

This project leverages Machine Learning to predict the presence of heart disease in patients based on various medical attributes (e.g., age, cholesterol, chest pain type).

## 🎯 Project Highlights
- **Exploratory Data Analysis (EDA):** Discovered that Chest Pain Type (`cp`) has the highest positive correlation with heart disease in this dataset.
- **Algorithm:** Trained a `RandomForestClassifier` achieving an initial accuracy of ~85%.
- **Medical-Grade Tuning:** In healthcare, False Negatives (telling a sick patient they are healthy) are fatal. I utilized `predict_proba` to lower the decision threshold to **30%**, drastically reducing False Negatives and prioritizing patient safety over raw accuracy.

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** (Data Manipulation)
- **Scikit-Learn** (Model Training, `train_test_split`, Evaluation)
- **Seaborn & Matplotlib** (Correlation Heatmaps, Confusion Matrix Visualization)

## 📂 Files
- `Heart_Disease_Prediction.ipynb`: The complete notebook with step-by-step code, analysis, and visualizations.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy scikit-learn seaborn matplotlib`.
3. Run the Jupyter Notebook to view the analysis and the effect of threshold tuning on the Confusion Matrix.
