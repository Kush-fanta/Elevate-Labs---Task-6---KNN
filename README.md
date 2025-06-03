# Elevate-Labs---Task-6---KNN
## Dataset

- **Name:** Iris Dataset
- **Source:** `sklearn.datasets.load_iris()`
- **Features Used:** 
  - sepal length (cm)
  - sepal width (cm)
  - petal length (cm)
  - petal width (cm)
- **Target:** Iris species (Setosa, Versicolor, Virginica)

---

## Steps Performed

1. **Loaded** the Iris dataset into a DataFrame.
2. **Preprocessed** the data:
   - Used all 4 numerical features
   - Normalized features using `StandardScaler`
3. **Split** the dataset into training and test sets.
4. **Trained** K-Nearest Neighbors (`KNeighborsClassifier`) with various `k` values.
5. **Evaluated** the model for each `k`:
   - Accuracy Score
   - Confusion Matrix
6. **Visualized** the decision boundaries using:
   - PCA to reduce from 4D to 2D
   - Mesh grid prediction on the PCA-reduced space

---

## Algorithms Used

- K-Nearest Neighbors (KNN)
- Principal Component Analysis (PCA)

---

## Evaluation Metrics

- Accuracy
- Confusion Matrix
- 2D Decision Boundary Plots (after PCA projection)

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
