 Breast Cancer Classification using SVM

Dataset
 Source: Breast Cancer Wisconsin Dataset
 Target: diagnosis column- M -> Malignant (1)- B -> Benign (0)
 Tools & Libraries Used- Python- Pandas & NumPy- Seaborn & Matplotlib- Scikit-learn (SVM, PCA, GridSearchCV, etc.)
 Project Workflow
 1. Data Loading & Exploration
   - Load data and visualize class distribution
 2. Data Preprocessing
   - Encode target, drop irrelevant columns, select features
 3. Feature Scaling
   - Normalize features using StandardScaler
 4. Model Training (SVM)
   - Linear, Polynomial, and RBF kernel SVMs
 5. Evaluation
   - Accuracy, Confusion Matrix, Classification Report
 6. Decision Boundary Visualization
   - Custom function using selected features and PCA
 7. Dimensionality Reduction
   - PCA for 2D projection
 8. Hyperparameter Tuning
   - GridSearchCV for best parameters and CV accuracy
 Results Summary- RBF kernel performed best after tuning.- PCA allowed 2D visualization of decision regions.- GridSearchCV improved generalization.
 Sample Output
 Accuracy: 0.9561
Confusion Matrix:
 Actual Negative (0): 72
 Actual Positive (1): 38
 False Positives: 1
 False Negatives: 3
 How to Run
 1. Clone the repository:
   git clone https://github.com/yourusername/breast-cancer-svm.git
 2. Install required packages:
   pip install -r requirements.txt
 3. Run the script:
   python breast_cancer_svm.py
 Future Improvements- Add more classifiers (e.g., Random Forest)- Deploy using Streamlit- Feature selection and model explainability
