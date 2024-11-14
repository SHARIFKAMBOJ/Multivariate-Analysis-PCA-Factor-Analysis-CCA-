# Multivariate Analysis on Pima Diabetes Dataset  

This repository contains the analysis of the **Pima Diabetes Dataset**, focusing on multivariate statistical techniques, preprocessing steps, and machine learning models to explore and classify diabetes-related data.  

## Project Overview  

The project aims to:
- Preprocess data to handle missing values, outliers, and feature scaling.
- Apply dimensionality reduction using **PCA** and **Factor Analysis**.
- Perform clustering with techniques such as **Hierarchical Clustering** (Single, Complete, Average, Ward's Linkages) and **K-Means**.  
- Conduct **Canonical Correlation Analysis (CCA)** and evaluate relationships between variable sets.  
- Model data using **Logistic Regression** for binary classification.
- Visualize results with **Biplots** and other statistical plots.

---

## Dataset  

The dataset used is the **Pima Diabetes Dataset**, which includes the following features:  

- **Pregnancies**: Number of pregnancies.  
- **Glucose**: Plasma glucose concentration.  
- **BloodPressure**: Diastolic blood pressure.  
- **SkinThickness**: Triceps skinfold thickness.  
- **Insulin**: 2-Hour serum insulin.  
- **BMI**: Body Mass Index.  
- **DiabetesPedigreeFunction**: Diabetes pedigree function score.  
- **Age**: Patient age in years.  
- **Outcome**: Binary variable indicating the presence (1) or absence (0) of diabetes.

---

## Analysis Workflow  

### 1. **Data Preprocessing**  
- **Handling Missing Data**: Imputed missing values using appropriate statistical techniques.  
- **Outlier Detection**: Identified and managed outliers in features like Glucose and Insulin.  
- **Scaling**: Standardized features using Min-Max Scaling or Standard Scaler.  

---

### 2. **Dimensionality Reduction**  
- **Principal Component Analysis (PCA)**: Reduced dimensions while retaining 95% variance; used 7 principal components.  
- **Factor Analysis**: Extracted underlying latent factors from the dataset.  

---

### 3. **Clustering**  
- **Hierarchical Clustering**:  
  - Performed with Single, Complete, Average, and Ward's Linkages.  
- **K-Means Clustering**:  
  - Determined optimal clusters using the Elbow Method and Silhouette Scores.  

---

### 4. **Canonical Correlation Analysis (CCA)**  
- Explored relationships between predictor variables and target outcomes.  

---

### 5. **Modeling with Logistic Regression**  
- Built and evaluated a **Logistic Regression Model** to predict diabetes outcomes.  

---

### 6. **Visualization**  
- Created **Biplots** to visualize PCA components.  
- Cluster visualizations for K-Means and Hierarchical Clustering.  
- Correlation heatmaps and pair plots for feature relationships.  

---

## Key Results  

- **PCA** explained 95% variance using 7 components.  
- Identified meaningful clusters using **Ward's Linkage** and **K-Means**.  
- Logistic Regression achieved an accuracy of XX% (replace XX with your result).  

---

## Repository Contents  

- `data/`: Contains the dataset and any processed data files.  
- `notebooks/`: Jupyter notebooks with detailed analysis and results.  
- `src/`: Python scripts for preprocessing, modeling, and visualization.  
- `plots/`: Saved visualizations like biplots and cluster plots.  
- `README.md`: Project documentation (this file).  

---

## How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/pima-diabetes-analysis.git
   cd pima-diabetes-analysis
