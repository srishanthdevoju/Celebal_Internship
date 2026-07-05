````markdown
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
│   └── plots/
│       └── (generated visualizations)
│
├── Week3/
│   ├── week3_srishanthdevoju.ipynb
│   ├── models/
│   │   ├── stacking_meta_model.pkl
│   │   └── standard_scaler.pkl
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
│   ├── models/
│   │   ├── cnn_model_v2_final.h5
│   │   └── aug_cnn_model_final.h5
│   └── plots/
│       ├── sampledata.png
│       ├── plot_ann_train_val_metrics.png
│       ├── plot_ann_v2_train_val_metrics.png
│       ├── plot_cnn_train_val_metrics.png
│       ├── plot_cnn_v2_train_val_metrics.png
│       ├── plot_cnn_v2_improved_train_val_metrics.png
│       ├── plot_cnn_v3_20epochs_train_val_metrics.png
│       ├── plot_cnn_v4_early_stopping_train_val_metrics.png
│       ├── plot_aug_cnn_train_val_metrics.png
│       ├── plot_all_models_val_accuracy.png
│       ├── plot_3_ann_original_vs_increased_layers_vs_cnn.png
│       ├── plot_4_all_models_increased_filters_val_accuracy.png
│       ├── plot_5_all_models_early_stopping_val_accuracy.png
│       └── plot_6_all_models_data_augmentation_val_accuracy.png
│
├── Week5/
│   ├── week5_srishanthdevoju.ipynb
│   ├── models/
│   │   ├── gru_model.keras
│   │   ├── gru_model2_upgraded.keras
│   │   ├── lstm_model (1).keras
│   │   ├── lstm_model2_upgraded.keras
│   │   ├── rnn_model.keras
│   │   └── rnn_model2_upgraded.keras
│   └── plots/
│       ├── training_accuracy_comparison_original.png
│       ├── training_accuracy_comparison_upgraded.png
│       ├── training_loss_comparison_original.png
│       └── training_loss_comparison_upgraded.png
│
├── Week6/
│   ├── week6_srishanthdevoju.ipynb
│   ├── models/
│   │   └── denoising_autoencoder_mnist.keras
│   └── plots/
│       ├── bottleneck_feature_maps.png
│       ├── denoising_at_various_noise_levels.png
│       ├── denoising_autoencoder_results.png
│       ├── model.png
│       ├── original_vs_noisy_images.png
│       └── training_history.png
│
└── README.md
```

---

# Week 1

## Topic

Introduction to Python, Data Analysis, and Exploratory Data Analysis (EDA).

### Notebook

- `week1_srishanthdevoju.ipynb`

### Learning Outcomes

- Python fundamentals
- NumPy and Pandas
- Data cleaning
- Exploratory Data Analysis
- Data visualization

### Outputs

- Data preprocessing
- Statistical summaries
- Visual analysis

---

# Week 2

## Topic

Time Series Forecasting and Regression Analysis.

### Notebook

- `week2_srishanthdevoju.ipynb`

### Models

- ARIMA
- VAR
- Linear Regression
- Tuned Ridge Regression
- Tuned Lasso Regression

### Outputs

- Forecasting models
- Regression models
- Performance evaluation
- Time series visualizations

### Key Findings

- Implemented statistical forecasting models.
- Compared regression techniques.
- Evaluated models using standard metrics.
- Visualized forecasting performance.

---

# Week 3

## Topic

Country Segmentation using Unsupervised Machine Learning.

### Notebook

- `week3_srishanthdevoju.ipynb`

### Techniques

- Data Preprocessing
- PCA
- K-Means Clustering
- DBSCAN
- Hierarchical Clustering
- K-Medoids

### Outputs

- Country segmentation
- Cluster visualizations
- PCA analysis
- Feature importance

### Key Findings

- PCA effectively reduced dimensionality.
- Compared multiple clustering algorithms.
- Identified meaningful country groups.
- Generated business insights from clusters.

---

# Week 4

## Topic

Image Classification using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) on the CIFAR-10 Dataset.

### Notebook

- `week4_srishanthdevoju.ipynb`

### Models Implemented

1. ANN (Original)
2. ANN (Increased Layers)
3. CNN (Original)
4. CNN (Increased Filters)
5. CNN (20 Epochs)
6. CNN with Early Stopping
7. CNN with Data Augmentation

### Final Results

| Model | Test Accuracy |
|--------|--------------:|
| ANN (Original) | 41.70% |
| ANN (Increased Layers) | 39.15% |
| CNN (Original) | 73.01% |
| CNN (Increased Filters) | 75.37% |
| CNN (20 Epochs) | 76.31% |
| CNN (Early Stopping) | **77.92%** |
| CNN (Data Augmentation) | 65.64% |

### Outputs

- Trained ANN models
- Trained CNN models
- Accuracy comparison plots
- Loss comparison plots

### Key Findings

- CNNs significantly outperformed ANNs.
- Increasing filters improved accuracy.
- Additional epochs enhanced learning.
- Early stopping achieved the best generalization.
- Data augmentation reduced overfitting but lowered accuracy in this implementation.

---

# Week 5

## Topic

Sequence Modeling using Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Units (GRU).

### Notebook

- `week5_srishanthdevoju.ipynb`

### Models Implemented

1. Simple RNN
2. Upgraded Simple RNN
3. LSTM
4. Upgraded LSTM
5. GRU
6. Upgraded GRU

### Outputs

- Trained RNN models
- Trained LSTM models
- Trained GRU models
- Accuracy comparison plots
- Loss comparison plots

### Key Findings

- LSTM effectively captured long-term dependencies.
- GRU achieved competitive performance with fewer parameters.
- Upgraded architectures converged faster.
- Comparative analysis highlighted strengths of each recurrent architecture.

---

# Week 6

## Topic

Image Denoising using a Convolutional Denoising Autoencoder on the MNIST Dataset.

### Notebook

- `week6_srishanthdevoju.ipynb`

### Model Implemented

- Convolutional Denoising Autoencoder

### Outputs

- Trained denoising autoencoder
- Reconstructed images
- Feature map visualization
- Model architecture
- Training history
- Performance across multiple noise levels

### Key Findings

- Successfully reconstructed clean images from noisy inputs.
- Learned meaningful latent representations.
- Demonstrated robust denoising across different noise levels.
- Visualized bottleneck feature maps for model interpretability.
- Achieved effective image restoration while preserving digit structure.

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Statsmodels
- Jupyter Notebook

---

# Repository Highlights

- Machine Learning
- Deep Learning
- Time Series Forecasting
- Regression Analysis
- Unsupervised Learning
- Image Classification
- Sequence Modeling
- Autoencoders
- Data Visualization
- Model Evaluation

---

# Author

**Srishanth Devoju**

GitHub: https://github.com/srishanthdevoju
````
