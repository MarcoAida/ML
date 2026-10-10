# ML

## Heart Disease Classification with k-NN
**Machine Learning Project — Heart Disease UCI Dataset**

This project performs classification on the Heart Disease UCI dataset using the k-Nearest Neighbors (k-NN) algorithm. It builds on standard k-NN implementations and extends it with:
- Preprocessing for a real-world clinical dataset (missing values, categorical encoding, feature scaling).
- Systematic search over `k`.
- k-fold cross-validation using `StratifiedKFold`.
- Comparison of distance metrics (Euclidean, Manhattan, Minkowski).
- Comprehensive evaluation metrics (accuracy, precision, recall, F1-score, confusion matrix).

### Dataset
The project uses the **Heart Disease UCI** dataset (Cleveland subset, 303 patients, 13 features + target).
It can be loaded using the `ucimlrepo` Python package or from a local CSV file. The dataset includes clinical features such as age, sex, chest pain type (cp), resting blood pressure (trestbps), serum cholesterol (chol), and more.
