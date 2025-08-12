#  Fraud Detection with LightGBM

This project demonstrates how to build, explain, and evaluate a **fraud detection model** using **LightGBM**.  
It includes **feature engineering**, **SHAP explainability**, and **model performance evaluation** to identify key predictors of fraud.

---

##  Project Structure


---

## 📊 Features

- **Data Preprocessing**
  - Handling missing values
  - Outlier detection
  - Multicollinearity check

- **Feature Engineering**
  - Transformations & encoding
  - Behavioral feature creation
  - SHAP-based feature selection

- **Modeling**
  - LightGBM classifier
  - Hyperparameter tuning
  - Probability threshold tuning

- **Explainability**
  - SHAP value analysis for feature importance
  - Interpretation of top predictors

- **Evaluation**
  - Precision, Recall, F1-score, AUC
  - Calibration and validation results

---

## 📦 Setup

### 1️⃣ Clone the repository

```bash
# Install Git LFS (macOS example)
brew install git-lfs

# Enable Git LFS
git lfs install

# Clone the repo
git clone <YOUR_REPO_URL>
cd fraud-detection-lightgbm
# Install dependencies
pip install -r requirements.txt
```


## 📌 Dataset
The dataset (Fraud.csv, ~471 MB) is stored in data/ and managed via Git Large File Storage (Git LFS).
If you clone without Git LFS, you’ll only get a pointer file instead of the full CSV.

📈 Results
Top predictors of fraud identified via SHAP analysis.

-Model achieves strong Recall for fraud cases, ensuring minimal missed detections.

-Explainable AI methods provide transparency in fraud prevention strategies.

