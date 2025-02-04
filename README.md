## Lab 2.2: Multi-Class Classification with One-vs-All Logistic Regression and k-Nearest Neighbors on the Forest Cover Type Dataset 🌲    

[Notebook](https://albanecoiffe.github.io/forest_cover_type_dataset/)

## 🎯 Objective
This project aims to classify different forest cover types using two machine learning algorithms:
- One-vs-All Logistic Regression
- k-Nearest Neighbors (k-NN)      
The dataset used is the Forest Cover Type Dataset from the UCI Machine Learning Repository. Before classification, an exploratory data analysis (EDA) is conducted using ydata_profiling.

## 📊 Dataset Description
- Name: Forest Cover Type Dataset
- Classes: 7 different forest cover types (Spruce/Fir, Lodgepole Pine, etc.)
- Features: 54 cartographic attributes (elevation, slope, soil type, etc.)
- Size: 581,012 samples

 
## ⚙️ Project Phases
1. Dataset Profiling with ydata_profiling
Generating a profiling report to explore dataset characteristics (missing values, outliers, correlations, etc.).

2. Data Preprocessing
- Feature engineering
- Splitting the dataset into training (80%) and testing (20%) sets
- Standardizing data to improve model convergence

3. Model Training & Evaluation
✅ One-vs-All Logistic Regression
 - Training the model using the One-vs-All strategy
 - Evaluating performance using a confusion matrix and a classification report
✅ k-Nearest Neighbors (k-NN)
 - Training the k-NN model
 - Evaluating performance similarly to logistic regression

4. Analysis & Discussion
- Comparing the performance of both models
- Exploring hyperparameters (e.g., different values of k for k-NN and regularization tuning for logistic regression)
- Using cross-validation for more robust evaluation      

## 🛠️ Technologies Used
- Python: Programming language for analysis and modeling
- Pandas & NumPy: Data manipulation and preprocessing
- Matplotlib & Seaborn: Data visualization
- scikit-learn: Machine learning model implementation
- ydata_profiling: Automated dataset exploration reports
