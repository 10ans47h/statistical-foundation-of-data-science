# Breast Cancer Classification Using PCA

## Project Information
- **University:** Shoolini University
- **Practical:** P2
- **Topic:** Principal Component Analysis (PCA)

## Description
This project implements Principal Component Analysis (PCA) using Python and the Breast Cancer dataset from Scikit-learn.

The project uses PCA and Logistic Regression to classify breast cancer data using different numbers of principal components.

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
The built-in Breast Cancer dataset from Scikit-learn is used.

- Total Samples: 569
- Total Features: 30
- Training Data: 70%
- Testing Data: 30%
- Random State: 42

## Implementation
The Python code performs:

1. Dataset loading.
2. Training and testing data splitting.
3. PCA on raw data.
4. Data standardisation.
5. PCA on standardised data.
6. Logistic Regression using PCA.
7. Accuracy calculation for k = 2, 5, 10 and 30.
8. Accuracy comparison table.
9. Accuracy visualisation using Matplotlib.

## Execution
The code can be executed using:
- Google Colab
- Jupyter Notebook
- Python IDE

Install required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Output
The program generates:
- Explained variance of PC1.
- Dominant feature in raw PCA.
- Classification accuracy for different PCA components.
- Accuracy comparison table.
- PCA accuracy graph.
