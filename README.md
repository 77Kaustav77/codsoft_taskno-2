#  Task 2 - Credit Card Fraud Detection (CodSoft Internship)

This project focuses on detecting fraudulent transactions using Random Forest and Decision Tree classifiers on a cleaned and balanced dataset.

---

##  Dataset

- Contains customer transaction records with columns like `amount`, `merchant`, `job`, `category`, and `is_fraud`
- Extracted from a ZIP file and loaded using pandas
- Preprocessed by:
  - Dropping irrelevant columns (`cc_num`, `trans_num`, `unix_time`, etc.)
  - Calculating `age` from date of birth
  - Encoding categorical features (`gender`, `job`, `merchant`, etc.)
  - Balancing the dataset (fraud vs non-fraud)

---

## Tools Used

- Python
- pandas
- scikit-learn
- RandomForestClassifier
- DecisionTreeClassifier
- matplotlib (for visualization)

---

## Steps Performed

1. Loaded and cleaned the dataset
2. Engineered new features like age
3. Encoded categorical data using LabelEncoder
4. Balanced the dataset to fix class imbalance
5. Trained a **Random Forest** and a **Decision Tree** model
6. Evaluated both using:
   - Accuracy
   - Classification Report
   - Confusion Matrix

---



## 📈 Visualization

- Bar plot for predicted fraud vs non-fraud
- Confusion matrix heatmap to show TP, FP, FN, and TN

---

##  Results

- **Random Forest Accuracy**: High precision for fraud detection
- **Decision Tree**: Slightly lower but explainable model
- Clear improvement after balancing classes

