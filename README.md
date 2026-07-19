# Celebal Technologies Internship

This repository contains my weekly assignments, trained models, visualizations, and notebooks completed during the **Celebal Technologies Internship Program**. Each week focuses on different Machine Learning, Deep Learning, and Generative AI concepts, progressing from data analysis and forecasting to computer vision, sequence modeling, autoencoders, and Retrieval-Augmented Generation (RAG).

---

# Repository Structure

```text
Celebal_Internship/
│
├── week1_srishanthdevoju.ipynb
│
├── week2_srishanthdevoju.ipynb
├── week2_models/
│   ├── arima_model.pkl
│   ├── linear_regression_model.pkl
│   ├── tuned_lasso_regression_model.pkl
│   ├── tuned_ridge_regression_model.pkl
│   └── var_model.pkl
├── week2_plots/
│   └── (generated visualizations)
│
├── week3_srishanthdevoju.ipynb
├── week3_models/
│   ├── stacking_meta_model.pkl
│   └── standard_scaler.pkl
├── week3_plots/
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── elbow_method_marked.png
│   ├── feature_distributions.png
│   ├── feature_importance.png
│   ├── gdpp_vs_income.png
│   ├── outlier_boxplots.png
│   ├── pca_clusters.png
│   ├── pca_dbscan.png
│   ├── pca_hierarchical.png
│   └── pca_kmedoids.png
│
├── week4_srishanthdevoju.ipynb
├── week4_models/
│   ├── cnn_model_v2_final.h5
│   └── aug_cnn_model_final.h5
├── week4_plots/
│   ├── sampledata.png
│   ├── plot_ann_train_val_metrics.png
│   ├── plot_ann_v2_train_val_metrics.png
│   ├── plot_cnn_train_val_metrics.png
│   ├── plot_cnn_v2_train_val_metrics.png
│   ├── plot_cnn_v2_improved_train_val_metrics.png
│   ├── plot_cnn_v3_20epochs_train_val_metrics.png
│   ├── plot_cnn_v4_early_stopping_train_val_metrics.png
│   ├── plot_aug_cnn_train_val_metrics.png
│   ├── plot_all_models_val_accuracy.png
│   ├── plot_3_ann_original_vs_increased_layers_vs_cnn.png
│   ├── plot_4_all_models_increased_filters_val_accuracy.png
│   ├── plot_5_all_models_early_stopping_val_accuracy.png
│   └── plot_6_all_models_data_augmentation_val_accuracy.png
│
├── week5_srishanthdevoju.ipynb
├── week5_models/
│   ├── rnn_model.keras
│   ├── rnn_model2_upgraded.keras
│   ├── lstm_model (1).keras
│   ├── lstm_model2_upgraded.keras
│   ├── gru_model.keras
│   └── gru_model2_upgraded.keras
├── week5_plots/
│   ├── training_accuracy_comparison_original.png
│   ├── training_accuracy_comparison_upgraded.png
│   ├── training_loss_comparison_original.png
│   └── training_loss_comparison_upgraded.png
│
├── week6_srishanthdevoju.ipynb
├── week6_models/
│   └── denoising_autoencoder_mnist.keras
├── week6_plots/
│   ├── bottleneck_feature_maps.png
│   ├── denoising_at_various_noise_levels.png
│   ├── denoising_autoencoder_results.png
│   ├── model.png
│   ├── original_vs_noisy_images.png
│   └── training_history.png
│
├── week7_srishanthdevoju.ipynb
│
|__ week8_srishanthdevoju.ipynb
└── README.md
```

---

# Week 1

## Topic

Introduction to Python, Data Analysis, and Exploratory Data Analysis (EDA).

### Notebook

* `week1_srishanthdevoju.ipynb`

### Learning Outcomes

* Python Programming Fundamentals
* NumPy
* Pandas
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization

### Outputs

* Data preprocessing
* Statistical analysis
* Exploratory visualizations

---

# Week 2

## Topic

Time Series Forecasting and Regression Analysis.

### Notebook

* `week2_srishanthdevoju.ipynb`

### Models

* ARIMA
* VAR
* Linear Regression
* Tuned Ridge Regression
* Tuned Lasso Regression

### Outputs

* Forecasting models
* Regression models
* Model evaluation
* Time series visualizations

### Key Findings

* Implemented multiple forecasting techniques.
* Compared regression algorithms.
* Evaluated prediction performance using standard metrics.
* Generated forecasting visualizations.

---

# Week 3

## Topic

Country Segmentation using Unsupervised Machine Learning.

### Notebook

* `week3_srishanthdevoju.ipynb`

### Techniques

* Data Preprocessing
* Principal Component Analysis (PCA)
* K-Means Clustering
* DBSCAN
* Hierarchical Clustering
* K-Medoids

### Outputs

* Cluster analysis
* PCA visualization
* Feature importance
* Country segmentation insights

### Key Findings

* Reduced dimensionality using PCA.
* Compared multiple clustering algorithms.
* Identified meaningful country clusters.
* Derived insights from segmented groups.

---

# Week 4

## Topic

Image Classification using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) on the CIFAR-10 Dataset.

### Notebook

* `week4_srishanthdevoju.ipynb`

### Models Implemented

1. ANN (Original)
2. ANN (Increased Layers)
3. CNN (Original)
4. CNN (Increased Filters)
5. CNN (20 Epochs)
6. CNN with Early Stopping
7. CNN with Data Augmentation

### Final Results

| Model                   | Test Accuracy |
| ----------------------- | ------------: |
| ANN (Original)          |        41.70% |
| ANN (Increased Layers)  |        39.15% |
| CNN (Original)          |        73.01% |
| CNN (Increased Filters) |        75.37% |
| CNN (20 Epochs)         |        76.31% |
| CNN (Early Stopping)    |    **77.92%** |
| CNN (Data Augmentation) |        65.64% |

### Outputs

* Trained ANN models
* Trained CNN models
* Performance comparison plots
* Training history

### Key Findings

* CNN significantly outperformed ANN.
* Increasing filters improved feature extraction.
* More epochs improved model performance.
* Early stopping provided the best generalization.
* Data augmentation reduced overfitting but slightly decreased final accuracy.

---

# Week 5

## Topic

Sequence Modeling using Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Units (GRU).

### Notebook

* `week5_srishanthdevoju.ipynb`

### Models Implemented

1. Simple RNN
2. Upgraded Simple RNN
3. LSTM
4. Upgraded LSTM
5. GRU
6. Upgraded GRU

### Outputs

* Trained RNN models
* Trained LSTM models
* Trained GRU models
* Training accuracy comparison
* Training loss comparison

### Key Findings

* LSTM captured long-term dependencies effectively.
* GRU achieved competitive performance with fewer parameters.
* Upgraded architectures improved convergence and learning stability.
* Compared the strengths and limitations of recurrent neural network architectures.

---

# Week 6

## Topic

Image Denoising using a Convolutional Denoising Autoencoder on the MNIST Dataset.

### Notebook

* `week6_srishanthdevoju.ipynb`

### Model Implemented

* Convolutional Denoising Autoencoder

### Outputs

* Trained denoising autoencoder
* Image reconstruction results
* Bottleneck feature visualization
* Model architecture
* Training history
* Performance across multiple noise levels

### Key Findings

* Successfully reconstructed clean handwritten digits from noisy images.
* Learned compact latent feature representations.
* Demonstrated robust denoising capability across different noise levels.
* Visualized bottleneck feature maps for better model interpretability.

---

# Week 7

## Topic

Document Question Answering System using Retrieval-Augmented Generation (RAG).

### Notebook

* `week7_srishanthdevoju.ipynb`

### Project Overview

Developed a Retrieval-Augmented Generation (RAG) system that allows users to upload custom documents and ask questions in natural language. The system retrieves the most relevant document chunks using semantic search and leverages a Large Language Model (LLM) to generate accurate, context-aware answers grounded in the uploaded documents.

### Features

* Upload PDF, TXT, and DOCX documents
* Automatic text extraction and preprocessing
* Document chunking for efficient retrieval
* Semantic search using vector embeddings
* Context-aware question answering
* Interactive notebook-based interface
* Source-grounded response generation

### Technologies Used

* LangChain
* Hugging Face Embeddings
* Groq API
* Large Language Models (LLMs)

### Outputs

* Document ingestion pipeline
* Text chunking and embedding generation
* Vector database creation
* Semantic document retrieval
* Context-aware answer generation
* Interactive document question-answering system

### Key Findings

* Built an end-to-end Retrieval-Augmented Generation (RAG) pipeline.
* Improved response accuracy using semantic retrieval before generation.
* Reduced hallucinations by grounding responses in uploaded documents.
* Demonstrated practical application of LLMs for document-based question answering.

---

# Week 8

## Topic

Single-Agent Smart Assistant with Intent Routing and Tool Integration.

### Notebook

* `week8_srishanthdevoju.ipynb`

### Project Overview

Developed a Single-Agent Smart Assistant capable of understanding user queries, identifying user intent, and routing each request to the appropriate tool or response module. The assistant integrates multiple utilities into a single intelligent pipeline and returns structured JSON responses, making it suitable for AI-powered applications, automation workflows, and backend services.

### Problem Statement

Build a **Single-Agent Smart Assistant** that:

- Understands user queries
- Routes tasks based on intent
- Uses tools when required
- Returns structured JSON output

The assistant should handle:

- Math queries → Calculator Tool
- Keyword extraction → Keyword Tool
- General queries → Direct response

### Features

* Intent detection and query classification
* Conditional routing based on user intent
* Calculator tool for mathematical operations
* Keyword extraction from text
* General query handling
* Structured JSON response generation
* Basic error handling
* Logging for debugging and monitoring
* Modular and extensible architecture
* Easy integration of additional tools

### Technologies Used

* Python
* JSON
* Regular Expressions (Regex)
* Object-Oriented Programming (OOP)

### Outputs

* Intent classification
* Query routing pipeline
* Calculator tool execution
* Keyword extraction results
* General query responses
* Structured JSON outputs
* Error handling for invalid queries
* Logging information

### Key Findings

* Built a modular Single-Agent architecture capable of handling multiple categories of user requests.
* Implemented intent-based routing to dispatch queries to specialized tools.
* Produced consistent JSON responses suitable for API and backend integration.
* Demonstrated intelligent tool orchestration through conditional routing.
* Improved maintainability by separating routing logic from tool implementations.
* Added logging and error handling to improve reliability and simplify debugging.
* Designed the assistant to be easily extensible by allowing new tools to be integrated with minimal modifications.

---

# Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* Statsmodels
* LangChain
* FAISS
* Hugging Face Embeddings
* Groq API
* Jupyter Notebook


---

# Author

**Srishanth Devoju**

GitHub: https://github.com/srishanthdevoju
