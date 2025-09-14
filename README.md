💊 Drug Prediction — Decision Tree

A clear and interpretable baseline for predicting drug categories using patient features and a Decision Tree classifier. Designed to be interview-friendly, with emphasis on clarity, step-by-step decisions, and interpretability.

📂 Project Structure
<p align="left">├── Drug_Prediction_DecisionTree_polished.ipynb <p align="center">
<p align="left">├── README.md <p align="left"> 
<p align="left">├── data/ <p align="left">                                       
<p align="left">├── images/ <p align="left">                                  
<p align="left">└── requirements.txt <p align="left">                           

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

<p align="center"> <img width="486" height="468" src="<img width="465" height="466" alt="image" src="C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\Screenshot 2025-09-14 102951.png" />
" alt="Dataset Preview"/> </p>

🔹 Category Counts

<p align="center"> <img width="702" height="605" src="<img width="705" height="603" alt="image" src=""C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\Screenshot 2025-09-14 102906.png"" />
" alt="Category Counts"/> </p>

🔹 Model Accuracy

<p align="center"> <img width="722" height="38" src="<img width="647" height="41" alt="image" src=""C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\Screenshot 2025-09-14 102815.png" />
" alt="Model Accuracy"/> </p>

🔹 Confusion Matrix

<p align="center"> <img width="642" height="485" src=""C:\Users\ShAmiR\OneDrive\Pictures\Screenshots\Screenshot 2025-09-14 102717.png"" />
" alt="Confusion Matrix"/> </p>

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
