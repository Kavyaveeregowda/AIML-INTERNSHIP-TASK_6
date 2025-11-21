# AIML-INTERNSHIP-TASK_6
KNN model applied on Iris dataset with preprocessing, model evaluation, and decision boundary visualization as per task requirements.

# AIML Task 6 – KNN Classification

## Objective
Implement K-Nearest Neighbors (KNN) classifier on a suitable dataset and analyse the performance for different K values.

## Dataset
- Dataset used: Iris dataset
- Features: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm
- Target: Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Steps Performed
1. Loaded the Iris dataset using pandas.
2. Performed basic EDA (head, info, shape, null value check).
3. Selected feature matrix (X) and target vector (y).
4. Split the dataset into training and testing sets (80% train, 20% test).
5. Normalized the features using StandardScaler.
6. Trained KNN models for K values from 1 to 20.
7. Plotted K vs Accuracy graph.
8. Selected the best K value based on accuracy.
9. Evaluated the final model using accuracy, confusion matrix and classification report.
10. Plotted decision boundary using two features (SepalLengthCm and SepalWidthCm).

## Results
- Best accuracy obtained: ~96.67%
- Confusion matrix shows very few misclassifications.
- KNN works well on the Iris dataset after feature scaling.

## Files
- `AIML_Task6_KNN.ipynb` – Jupyter Notebook with full implementation.
- `Iris.csv` – Dataset file (if included).
- `README.md` – Project description.

