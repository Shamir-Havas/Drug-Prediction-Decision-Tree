# <b>💊 Drug Prediction — Decision Tree  </b>

A clear and interpretable baseline for predicting **drug categories** using patient features and a Decision Tree classifier. Designed to be **interview-friendly**, with emphasis on clarity, step-by-step decisions, and interpretability.  

---

##<b> 📂 Project Structure  </b>

├── Drug_Prediction_DecisionTree_polished.ipynb # Main notebook with full workflow
├── README.md # Project documentation


---

##<b> ⚙️ Skills & Tech</b>  

- **Python, Jupyter Notebook**  
- **pandas, NumPy** — Data handling  
- **matplotlib, seaborn** — Visualization  
- **scikit-learn** — DecisionTreeClassifier, model evaluation  
- **EDA, Preprocessing, Model interpretation**  

---

## <b>📝 Project Overview  </b>

This notebook demonstrates a complete **Machine Learning workflow** for predicting drug categories:  

1. **Exploratory Data Analysis (EDA)** – Inspect dataset distribution and patterns  
2. **Preprocessing** – Encoding categorical features, handling data types  
3. **Model Training** – Decision Tree Classifier  
4. **Evaluation** – Accuracy, interpretability, decision paths  

---

##<b> 📊 Dataset</b>  

- **Features:**  
  - Age: Age of the patient  
  - Sex: Male/Female  
  - Blood Pressure: Low / Normal / High  
  - Cholesterol: Normal / High  
  - Na_to_K ratio: Sodium-to-Potassium ratio in the blood  
- **Target:** Drug type (DrugA, DrugB, DrugC, DrugX, DrugY)  
- **Size:** 200 samples  
- **Source:** UCI / educational dataset  

---

##<b> ▶️ How to Run</b>  

1. Clone or download this repository:  
   ```bash
   git clone https://github.com/Shamir-Havas/Drug-Prediction-Decision-Tree.git
   cd Drug-Prediction-Decision-Tree
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open Jupyter Notebook and run the workflow:

bash
Copy code
jupyter notebook Drug_Prediction_DecisionTree_polished.ipynb
Run all cells:

Kernel → Restart & Run All

<b>📊 Results</b><br>

🔹 Category Counts<br>

![Category Counts](https://raw.githubusercontent.com/Shamir-Havas/Drug-Prediction-Decision-Tree/main/category_counts.png)<br>

🔹 Decision Tree Visualization<br>

![Decision Tree](https://raw.githubusercontent.com/Shamir-Havas/Drug-Prediction-Decision-Tree/main/decision_tree.png)<br>

🔹 Model Accuracy<br>

![Model Accuracy](https://raw.githubusercontent.com/Shamir-Havas/Drug-Prediction-Decision-Tree/main/accuracy.png)<br>


<b>🔍 Model Explainability</b>


Decision Tree Visualization: Interpretable decision paths using plot_tree

Classification Report: Precision, recall, F1-score

<b>🚀 Future Improvements</b>

Hyperparameter tuning with GridSearchCV / RandomizedSearchCV

Cross-validation (e.g., Stratified K-Fold) for robustness

Try ensemble methods (Random Forest, XGBoost)

Domain-specific validation & feature engineering

<b>📦 Requirements</b>

pandas==2.0.3  
numpy==1.25.2  
matplotlib==3.7.2  
seaborn==0.12.2  
scikit-learn==1.3.0  
