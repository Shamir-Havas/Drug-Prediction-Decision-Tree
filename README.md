💊 Drug Prediction — Decision Tree

A clear and interpretable baseline for predicting drug categories using patient features and a Decision Tree classifier. Designed to be interview-friendly, with emphasis on clarity, step-by-step decisions, and interpretability.

📂 Project Structure<br>
├── Drug_Prediction_DecisionTree_polished.ipynb  <br>
├── README.md                                   

⚙️ Skills & Tech

Python, Jupyter Notebook

pandas, NumPy — Data handling

matplotlib, seaborn — Visualization

scikit-learn — DecisionTreeClassifier, model evaluation

EDA, Preprocessing, Model interpretation

📝 Project Overview

This notebook demonstrates a complete Machine Learning workflow for predicting drug categories:

Exploratory Data Analysis (EDA) – Inspect dataset distribution and patterns

Preprocessing – Encoding categorical features, handling data types

Model Training – Decision Tree Classifier

Evaluation – Accuracy, confusion matrix, interpretability

📊 Dataset

Features:

Age: Age of the patient

Sex: Male/Female

Blood Pressure: Low / Normal / High

Cholesterol: Normal / High

Na_to_K ratio: Sodium-to-Potassium ratio in the blood

Target: Drug type (DrugA, DrugB, DrugC, DrugX, DrugY)

Size: 200 samples (balanced categories)

Source: UCI / educational dataset

▶️ How to Run

Clone or download this repository.

Place the dataset in the data/ folder (if not already included).

Open Drug_Prediction_DecisionTree_polished.ipynb in Jupyter Notebook.

Run all cells:

Kernel → Restart & Run All

📊 Results

🔹 Category Counts

Visualize the distribution of drug categories to assess class balance:


Replace this placeholder with a screenshot of your category distribution (e.g., bar chart showing the count of each drug type).

🔹 Model Accuracy

The model achieves an accuracy of ~97% on the test set


Replace this placeholder with your accuracy plot or printed output.

🔹 Confusion Matrix

To evaluate model performance, visualize the confusion matrix:


Replace this placeholder with a screenshot of your confusion matrix heatmap.


🔹 Decision Tree Visualization

Visualize the structure of the Decision Tree to understand decision paths:


Replace this placeholder with a screenshot of your Decision Tree plot (using plot_tree).

🔍 Model Explainability

Feature Importance: Features ranked by their contribution to model decisions.

Decision Tree Visualization: Interpretable decision paths using plot_tree.

Classification Report: Precision, recall, and F1-score.

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
