# TCGA Breast Cancer Prediction : Supervised & Unsupervised Learning Analysis

## 🚀 Supervised ML Steps Overview
It follows a systematic machine learning pipeline to analyze breast cancer gene expression data.

### Step 1: Data Preprocessing
* Cleaned and organized the raw TCGA genomic dataset.
* Handled 1936 gene features to prepare them for model training.

### Step 2: Exploratory Data Analysis (EDA)
* Performed visual analysis to understand gene distributions.
* Generated correlation heatmaps to identify relationships between key genes.

### Step 3: Model Training
* Implemented the **Random Forest Classifier**.
* This algorithm was chosen for its ability to handle complex biological datasets effectively.

### Step 4: Feature Importance
* Extracted the **Top 10 most influential genes** that drive the model's predictions.

### Step 5: Model Validation (Refined)
* Implemented **K-Fold Cross-Validation (cv=5)**.
* Applied `random_state=42` to ensure consistent and reproducible results.

### Final Results
* **Average Accuracy Achieved:** **88.37%**
* The model proved to be stable and reliable for clinical gene expression classification.

## 🛠️ Tools Used
* **Python**, **Scikit-Learn**, **Seaborn**, **Matplotlib**, **Google Colab**.
