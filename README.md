# ML-Task-5
 To implement and evaluate Decision Trees and Random Forests using Scikit-learn, and understand key concepts like overfitting, feature importance, and cross-validation.

# Task 5: Decision Trees and Random Forests - AI & ML Internship

## 📌 Objective
The objective of this task is to understand and implement **Decision Tree** and **Random Forest** classifiers using the **Heart Disease Dataset**. We explore key machine learning concepts like overfitting, feature importance, ensemble learning, and model evaluation.

---

## 🛠 Tools & Libraries Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- Graphviz (optional for tree visualization)

---

## 📁 Dataset
- **Name**: Heart Disease Dataset
- **Target Variable**: `target` (presence of heart disease)
- **Source**: [Kaggle / UCI Repository]

---

## 🔍 Steps Performed
1. **Data Loading and Preprocessing**
   - Loaded dataset and handled missing/null values if any.
   - Split the data into features (X) and target (y).

2. **Train-Test Split**
   - Split dataset using `train_test_split` from Scikit-learn (80/20 split).

3. **Decision Tree Classifier**
   - Trained a basic decision tree.
   - Visualized the tree using `plot_tree`.
   - Analyzed overfitting and controlled depth using `max_depth`.

4. **Random Forest Classifier**
   - Trained a Random Forest model with 100 estimators.
   - Compared performance with Decision Tree.

5. **Feature Importance**
   - Plotted feature importances to interpret key features.

6. **Cross-Validation**
   - Evaluated the model using 5-fold cross-validation for robustness.

---

## 📈 Results

| Model           | Train Accuracy | Test Accuracy |
|----------------|----------------|---------------|
| Decision Tree  | XX.XX%         | XX.XX%        |
| Random Forest  | XX.XX%         | XX.XX%        |

- Random Forest performed better and generalized well compared to the Decision Tree.
- Cross-validation score: **XX.XX%**

---

## 📊 Visuals Included
- Decision Tree diagram
- Feature importance bar chart
- Accuracy comparison

---

## 🤖 Concepts Learned
- Decision Tree construction using Gini/Entropy
- Information Gain & Overfitting control
- Random Forest as an ensemble of trees
- Feature importance interpretation
- Model evaluation via Cross-Validation

---

## 📂 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ai-ml-internship-task5.git
   cd ai-ml-internship-task5
