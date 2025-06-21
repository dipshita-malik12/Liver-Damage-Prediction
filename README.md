# 🩺 Liver Damage Prediction

This project predicts whether a patient has liver damage using classification algorithms like **Logistic Regression** and **K-Nearest Neighbors (KNN)**. The dataset contains clinical and demographic data of patients.

## 🎯 Objective

To build a machine learning model that can accurately predict liver damage based on patient attributes, assisting healthcare professionals in early detection and intervention.

---

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Explored data distributions and target class imbalance
- Visualized feature relationships using:
  - Histograms
  - Boxplots
  - Pairplots
  - Heatmaps

### 2. Data Preprocessing
- Handled missing or null values appropriately
- Encoded categorical columns using:
  - Label Encoding / One-Hot Encoding
- Scaled numerical features using:
  - `StandardScaler` or `MinMaxScaler`

### 3. Modeling
- Built models using:
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Score

---

## 📁 Project Structure

```text
liver-damage-prediction/
├── data/            # Raw and processed dataset files
├── notebooks/       # Jupyter notebooks for EDA and modeling
├── models/          # Saved model binaries (if any)
├── images/          # Visualizations and plots
├── src/             # Source code for preprocessing and modeling
├── README.md        # Project documentation
└── requirements.txt # List of required Python packages


🧪 Results
Logistic Regression

Accuracy: 98.61%


🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook

📬 Contact
For any queries or collaboration:
📧 dipshitamalik@gmail.com


