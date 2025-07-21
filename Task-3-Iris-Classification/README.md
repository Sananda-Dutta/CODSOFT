# Iris Flower Classification 🌸

| **Category**       | **Details**                                                                 |
|--------------------|----------------------------------------------------------------------------|
| **Objective**      | Classify Iris flowers into 3 species using measurements (sepal/petal)      |
| **Algorithms**     | Random Forest, SVM, KNN                                                    |
| **Best Accuracy**  | 90% (Random Forest)                                                        |
| **Dataset**        | [UCI Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)           |

---

## 📊 Results

### 1. Model Performance
![Classification Report](iris_classification_results_accuracy_0.9_20230721.png)  
- **Accuracy**: 90%  
- **Confusion Matrix**: Shows occasional misclassification between *versicolor* and *virginica*.  
- **Precision/Recall**: >0.9 for all classes.

### 2. Feature Importance
![Feature Importance Plot](iris_results_feature_importance.png)  
- **Top Features**:  
  - Petal length (46%)  
  - Petal width (42%)  
  - Sepal measurements (12% combined).

---

## 🛠️ How to Run

### Prerequisites
```bash
pip install pandas scikit-learn matplotlib seaborn

## 📸 Output Screenshots

<div align="center">
  <h3>1. Classification Report & Confusion Matrix</h3>
  <img src="images/confusion_matrix.png" alt="Classification Results" width="500"/>
  <p><em>Shows 90% accuracy with detailed precision/recall metrics</em></p>

  <h3>2. Feature Importance Analysis</h3>
  <img src="images/iris_Classification_result_1.png" alt="Feature Importance" width="500"/>
  <p><em>Petal measurements dominate classification importance</em></p>

  <h3>2. Feature Importance Analysis</h3>
  <img src="images/iris_Classification_result_2.png" alt="Feature Importance" width="500"/>
  <p><em>Petal measurements dominate classification importance</em></p>

</div>
## 📊 Key Results
| Metric               | Value  |
|----------------------|--------|
| **Best Accuracy**    | 90%    |
| **Misclassified**    | 3/30 (versicolor ↔ virginica) |
| **Top Feature**      | Petal length (46% importance) |

---

## 🛠️ Quick Start
1. **Add your screenshots** to the `/images` folder:
   ```bash
   mkdir images
   # Drag your screenshots into this folder
