💊 Drug Prediction — Decision Tree

A clear and interpretable baseline for predicting drug categories using patient features and a Decision Tree classifier. Designed to be interview-friendly, with emphasis on clarity, step-by-step decisions, and interpretability.

📂 Project Structure
├── Drug_Prediction_DecisionTree_polished.ipynb   # Main notebook with full workflow
├── README.md                                     # Project documentation
├── data/                                         # Dataset storage
├── images/                                       # Saved plots and figures
└── requirements.txt                              # Dependencies

⚙️ Skills & Tech

Python, Jupyter Notebook

pandas, NumPy — data handling

matplotlib, seaborn — visualization

scikit-learn — DecisionTreeClassifier, evaluation

EDA, preprocessing, model interpretation

📝 Project Overview

This notebook demonstrates a complete ML workflow for predicting drug categories:

Exploratory Data Analysis (EDA) – inspect dataset distribution and patterns

Preprocessing – encoding categorical features, handling data types

Model Training – Decision Tree Classifier

Evaluation – accuracy, confusion matrix, interpretability

📊 Dataset

Features: Age, Sex, Blood Pressure, Cholesterol, Na_to_K ratio

Target: Drug type (DrugA, DrugB, DrugC, DrugX, DrugY)

Size: 200 samples (balanced categories)

Source: UCI / educational dataset

▶️ How to Run

Clone or download this repository

Place the dataset in the data/ folder (if not already included)

Open Drug_Prediction_DecisionTree_polished.ipynb in Jupyter Notebook

Run all cells:

Kernel → Restart & Run All

📊 Results

🔹 Dataset Preview

<p align="center"> <img src=""C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\dataset_preview.png"" width="500" alt="Dataset Preview"/> </p>

🔹 Category Counts

<p align="center"> <img src=""C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\category_counts.png"" width="600" alt="Category Counts"/> </p>

🔹 Model Accuracy

<p align="center"> <img src="C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\model_accuracy.png" width="500" alt="Model Accuracy"/> </p>

🔹 Confusion Matrix

<p align="center"> <img src="C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\imagesconfusion_matrix.png" width="600" alt="Confusion Matrix"/> </p>
🔍 Model Explainability

Feature Importance: ranked by decision tree

Tree Visualization: interpretable decision paths using plot_tree

Classification Report: precision, recall, F1-score

🚀 Future Improvements

Hyperparameter tuning with GridSearchCV / RandomizedSearchCV

Cross-validation (e.g., Stratified K-Fold) for robustness

Try ensemble methods (Random Forest, XGBoost)

Domain-specific validation & feature engineering

📦 Requirements

pandas==2.0.3
numpy==1.25.2
matplotlib==3.7.2
seaborn==0.12.2
scikit-learn==1.3.0
