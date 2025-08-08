🧠 Parkinson’s Disease Detection using Machine Learning

This project focuses on building a predictive model using machine learning to detect Parkinson’s Disease based on biomedical voice measurements. The goal is to assist in early diagnosis using data-driven methods.

💡 Project Motivation
Diagnosing Parkinson’s Disease typically requires multiple clinical tests and expert evaluation. With the help of data science and machine learning, we can create tools that analyze voice patterns to predict the likelihood of the disease in a non-invasive and accessible way.

This project was developed to:
- Understand how biomedical voice features differ in Parkinson’s patients
- Apply machine learning algorithms to detect Parkinson’s
- Offer a simple method for healthcare researchers to replicate or build upon this work
- 
📂 Dataset Information
- **Samples:** 195 voice recordings
- **Subjects:** 31 individuals (23 with Parkinson’s, 8 healthy)
- **Features:** 24 biomedical voice measures extracted from speech recordings
- **Target:** `status` (1 = Parkinson’s, 0 = Healthy)

🛠️ Technologies Used

- **Python**
- **Pandas** for data handling
- **NumPy** for numerical computations
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for machine learning models (SVM, RandomForest, Logistic Regression)
- **StandardScaler** for feature scaling

🔁 Project Workflow

1. **Data Preprocessing**
   - Load and clean the dataset
   - Normalize features using `StandardScaler`
   - Split into train/test sets

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Class distribution checks
   - Feature distribution visualizations

3. **Model Building**
   - Algorithms: Support Vector Machine (SVM), Logistic Regression, Random Forest
   - Hyperparameter tuning
   - Cross-validation

4. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - Confusion matrix

5. **Prediction**
   - Accepts user input for real-time predictions

✅ Results
- The trained model achieved high accuracy using SVM, indicating good performance for classification.
- The model also supports custom prediction by entering biomedical measurements manually.
