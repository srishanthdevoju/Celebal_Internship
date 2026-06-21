# Celebal Internship

This repository contains my submissions, notebooks, trained models, visualizations, and analysis completed during the Celebal Technologies Internship Program.

---

# Repository Structure

```text
Celebal_Internship/
│
├── Week1/
│   └── week1_srishanthdevoju.ipynb
│
├── Week2/
│   ├── week2_srishanthdevoju.ipynb
│   ├── models/
│   │   ├── arima_model.pkl
│   │   ├── linear_regression_model.pkl
│   │   ├── tuned_lasso_regression_model.pkl
│   │   ├── tuned_ridge_regression_model.pkl
│   │   └── var_model.pkl
│   │
│   └── plots/
│       └── (generated visualizations)
│
├── Week3/
│   ├── week3_srishanthdevoju.ipynb
│   ├── models/
│   │   ├── stacking_meta_model.pkl
│   │   └── standard_scaler.pkl
│   │
│   └── plots/
│       ├── confusion_matrix.png
│       ├── correlation_heatmap.png
│       ├── elbow_method_marked.png
│       ├── feature_distributions.png
│       ├── feature_importance.png
│       ├── gdpp_vs_income.png
│       ├── outlier_boxplots.png
│       ├── pca_clusters.png
│       ├── pca_dbscan.png
│       ├── pca_hierarchical.png
│       └── pca_kmedoids.png
│
├── Week4/
│   ├── week4_srishanthdevoju.ipynb
│   │
│   ├── models/
│   │   ├── cnn_model_v2_final.h5
│   │   └── aug_cnn_model_final.h5
│   │
│   ├── plots/
│   │   ├── sampledata.png
│   │   ├── plot_ann_train_val_metrics.png
│   │   ├── plot_ann_v2_train_val_metrics.png
│   │   ├── plot_cnn_train_val_metrics.png
│   │   ├── plot_cnn_v2_train_val_metrics.png
│   │   ├── plot_cnn_v2_improved_train_val_metrics.png
│   │   ├── plot_cnn_v3_20epochs_train_val_metrics.png
│   │   ├── plot_cnn_v4_early_stopping_train_val_metrics.png
│   │   ├── plot_aug_cnn_train_val_metrics.png
│   │   ├── plot_all_models_val_accuracy.png
│   │   ├── plot_3_ann_original_vs_increased_layers_vs_cnn.png
│   │   ├── plot_4_all_models_increased_filters_val_accuracy.png
│   │   ├── plot_5_all_models_early_stopping_val_accuracy.png
│   │   └── plot_6_all_models_data_augmentation_val_accuracy.png
│   │
│   └── report/
│       └── CIFAR10_Project_Report.pdf
│
└── README.md
```

---

# Week 1

### Topic

Introduction to Python, Data Analysis, and Exploratory Data Analysis.

### Files

* `week1_srishanthdevoju.ipynb`

---

# Week 2

### Topic

Time Series Forecasting and Regression Analysis.

### Models

* ARIMA
* VAR
* Linear Regression
* Tuned Ridge Regression
* Tuned Lasso Regression

### Outputs

* Forecasting Models
* Evaluation Metrics
* Time Series Visualizations

---

# Week 3

### Topic

Country Segmentation using Unsupervised Machine Learning.

### Techniques

* Data Preprocessing
* PCA
* K-Means Clustering
* DBSCAN
* Hierarchical Clustering
* K-Medoids

### Outputs

* Cluster Analysis
* Feature Importance
* Country Segmentation Insights

---

# Week 4

### Topic

Image Classification using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) on the CIFAR-10 Dataset.

### Models Implemented

1. ANN (Original)
2. ANN (Increased Layers)
3. CNN (Original)
4. CNN (Increased Filters)
5. CNN (Increased Filters – 20 Epochs)
6. CNN with Early Stopping
7. CNN with Data Augmentation

### Final Results

| Model                              | Test Accuracy |
| ---------------------------------- | ------------- |
| ANN (Original)                     | 41.70%        |
| ANN (Increased Layers)             | 39.15%        |
| CNN (Original)                     | 73.01%        |
| CNN (Increased Filters)            | 75.37%        |
| CNN (Increased Filters, 20 Epochs) | 76.31%        |
| CNN (Early Stopping)               | **77.92%**    |
| CNN (Data Augmentation)            | 65.64%        |

### Key Findings

* CNNs significantly outperformed ANNs on image classification.
* Increasing filters improved feature extraction and accuracy.
* Training for more epochs improved performance.
* Early Stopping achieved the best generalization performance.
* Data Augmentation reduced overfitting but resulted in lower accuracy in this implementation.

---

# Author

**Srishanth Devoju**

GitHub: https://github.com/srishanthdevoju
