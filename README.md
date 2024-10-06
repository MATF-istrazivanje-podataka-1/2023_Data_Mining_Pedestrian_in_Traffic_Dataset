# Orbit Classification Data Mining Project

## Overview
This project applies various data mining techniques to the Orbit Classification dataset for pattern recognition, classification prediction, and data grouping.

## Dataset
The dataset used in this project is the ["Orbit Classification For Prediction / NASA"](https://www.kaggle.com/datasets/brsdincer/orbitclassification) dataset from Kaggle. It contains information about celestial bodies and their orbital characteristics.

## Techniques Used

1. **Data Preprocessing**
    
2. **Classification**: 
    - Decision Trees and KNN models were implemented for classification.
    - For KNN, SMOTEEN was used to balance class distribution.
    
3. **Clustering**: 
    - Similar objects were grouped using K-Means, Agglomerative Clustering, and DBSCAN.
    - Before clustering, Principal Component Analysis (PCA) was applied to reduce dimensionality.
    
4. **Association Rule Mining**: 
    - Applied the Apriori algorithm within IBM SPSS Modeler.

## Project Structure
```
├── dataset
│   └── classast-pha.csv
├── models
│   ├── association_rules
│   │   ├── associationRules.str
│   │   └── classast-pha.csv
│   ├── classification
│   │   ├── decision_tree_classifier.ipynb
│   │   └── KNN_classifier.ipynb
│   └── clustering
│       ├── agglomerative_clustering.ipynb
│       ├── dbscan_clustering.ipynb
│       └── k_means.ipynb
├── preprocessing
│   ├── data_preprocessed.csv
│   └── preprocess.ipynb
├── README.md
└── report
```

## Tools and Technologies
- Python 
- Jupyter Notebooks 
- Scikit-learn library for machine learning algorithms
- Pandas and NumPy libraries for data manipulation 
- Matplotlib and Seaborn for data visualization

## Results and Insights
Project results are documented in report/report.pdf.


