Creating my 1st readme.md file 
# HeartDiseasePrediction1202Assignment5

# Heart Disease Prediction using Machine Learning

## Dataset Information
- The dataset includes health-related attributes and labels to predict heart disease.
- Attributes include BMI, Smoking status, Physical Activity, Stroke history, and more.
- **Target Variable**: `HeartDisease` (Yes/No).
- The dataset is balanced and prepared for classification tasks.

## Overview
The project i have created predicts heart disease using Python and machine learning models. It processes health data to train and evaluate models like Decision Trees, Logistic Regression, KNN, MLP, and SVM.

## Getting Started
Follow all the instructions for setting up and run the project in any local machines which support the versions i am adding below.

### Prerequisites
- Python 3.8 or higher versions
- Pandas: Data manipulation and preprocessing.
- NumPy: Numerical computations.
- Scikit-learn: Machine learning algorithms and evaluation.
- Matplotlib & Seaborn: Data visualization.
- Jupyter Notebook: Interactive environment for code and analysis.

### Installing
1. Clone the repository:
   ```bash
   git clone https://github.com/anjiunnam/HeartDiseasePrediction.git
   
2. Installing required dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   
3. Navigate to project directory
   ```bash
   cd HeartDiseasePrediction
   
4. Run the code which i used for testing 
   ```bash
   jupyter notebook Assignment3_1200-Inroduction to Data Analysis.ipynb

### Breakdown of Tests
   
   - Model Training: Models used for training on the heart disease dataset are Decision Trees, Logistic Regression, KNN, MLP, and SVM.
   - Model Evaluation/Metrics: Measures accuracy, precision, recall, and F1 score.
   - Visualization: Plots feature importance and performance metrics.

### Deployment
   This project can be deployed on platforms like AWS, Azure, or Google Cloud using FastAPI for    the backend.

### Challenges 
1. **Handling Missing Data**:
   - Solution: Applied imputation techniques to fill missing values.
2. **Imbalanced Dataset**:
   - Solution: Used techniques like SMOTE (Synthetic Minority Oversampling) to balance the classes.
3. **Choosing the Right Model**:
   - Solution: Evaluated multiple models and selected the one with the best performance metrics.

### Results
- The Support Vector Machine (SVM) achieved the highest accuracy i.e., 87%.
- Logistic Regression showed the best precision score of 85%.
- Feature importance analysis revealed that `Age` and `PhysicalActivity` were the most             significant predictors of heart disease.

### Author
   Contact: anjiunnam1999@gmail.com

### Licence
   This project is licenced under the MIT License

### Acknowledgement
   - The Dataset used is from my professor Ziad Mohammad
   - Machine learning tools execution and learning from Data Analysis course in Durham college

