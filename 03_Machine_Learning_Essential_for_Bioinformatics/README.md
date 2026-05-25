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

## 🚀 Unsupervised ML Steps Overview
*Exploratory analysis of cancer genomic data using clustering techniques to identify patient subgroups.*

### **Step 1: Dimensionality Reduction (PCA)**
* **Applied Principal Component Analysis (PCA)** to reduce 1937 high-dimensional gene features into 2 primary components (PC1, PC2).
* This step successfully visualized complex genomic variations in a 2D space.

### **Step 2: Optimal Cluster Selection**
* Implemented the **Elbow Method** to calculate the Within-Cluster Sum of Squares (WCSS).
* Identified **3 optimal clusters** as the most significant grouping for the patient gene expression profiles.

### **Step 3: Clustering & Pattern Recognition**
* Executed **K-Means Clustering** to segment 705 patient samples into 3 distinct biological subgroups.
* Computed cluster **Centroids** to identify the central gene expression profile of each subgroup.

### **Step 4: Feature Importance (Biological Insights)**
* Extracted top influential genes contributing to cluster separation using PCA loadings.
* Identified key markers including **ESR1, FOXA1, AGR3, VGLL1, and ROPN1** that drive these phenotypic variations.

## 🛠 **Tools Used**
* **Languages:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
* **Platform:** Google Colab, GitHub
