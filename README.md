# UCI Adult Dataset Classification Using Random Forest

## 📌 Project Overview
This project implements a **Random Forest Classifier** to predict whether an individual earns more than **$50K per year** based on the **UCI Adult Dataset**. The dataset includes demographic and employment-related attributes extracted from the 1994 U.S. Census database.

## 📂 Dataset
The **UCI Adult Dataset** consists of **48,842** instances with **14 attributes**, including:
- **Categorical Features:** Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Native Country
- **Numerical Features:** Age, Hours-per-week, Education Level, Capital Gain, Capital Loss
- **Target Variable:** Income (<=50K or >50K)

The dataset is publicly available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries Used:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Model Used:** Random Forest Classifier

## 📊 Model Training & Evaluation
- **Training Accuracy:** **88%**
- **Testing Accuracy:** **83%**
- **Evaluation Metrics:**
  - **Confusion Matrix**
  - **ROC Curve (AUC = 0.96)**
  - **Precision, Recall, F1-score**

## 🔍 Key Findings
- The model shows **good generalization** but has a slight overfitting tendency.
- The **ROC curve (AUC = 0.96)** indicates strong discrimination capability.
- The dataset contains **class imbalance**, which might impact predictions.

## 🚀 Future Work
- Implement **deep learning models** to explore potential accuracy improvements.
- Update the model periodically with **new data** for better generalization.
- Apply **resampling techniques** to handle class imbalance.
- Consider adding **more relevant features** for improved predictive power.

## 📜 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uci-adult-rf-classifier.git
   cd uci-adult-rf-classifier
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python train_model.py
   ```
4. View results and visualizations in the generated output files.

## 💡 Conclusion
The **Random Forest Classifier** provides a solid baseline for income prediction using the **UCI Adult Dataset**. With further refinements, such as **handling class imbalance, adding features, and using deep learning models**, the prediction accuracy and fairness can be improved. 🚀

---
### 📬 Contact
For any queries, feel free to reach out via **[jubinkbabu5@gmail.com]**.

