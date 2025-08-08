
 Dataset
The dataset file `data.csv` contains:
- Diagnosis (`M` = Malignant, `B` = Benign)
- 30 numerical features describing cell nuclei characteristics.
- Extra columns (`id`, `Unnamed: 32`) removed during preprocessing.

---

 Steps in the Project
1. Load & Explore dataset.
2. Preprocess:
   - Drop unnecessary columns.
   - Encode target labels (`M` → 1, `B` → 0).
   - Train-test split and feature scaling.
3. Train Logistic Regression model.
4. Evaluate Model:
   - Confusion Matrix.
   - Precision, Recall, F1-score.
   - ROC Curve & AUC score.
5. Sigmoid Function:
   - Calculate predicted probabilities for a few samples.
6. Threshold Tuning:
   - Adjust classification cutoff to analyze precision-recall tradeoff.

--
