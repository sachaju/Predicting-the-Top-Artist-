# Spotify Top Artist Prediction (2023)

## Objective

The goal of this project is to predict the top artists on Spotify for the year 2023 using a dataset containing song streaming information. The project involves data cleaning, feature engineering, and applying machine learning techniques to segment artists into top performers and others. By analyzing various musical features and streaming data, the project identifies patterns in artist popularity. Several machine learning models, including **Random Forest**, **SVM**, **KNN**, and a **neural network**, are trained and evaluated. Additionally, clustering techniques like **PCA** (Principal Component Analysis) and **K-Means** are used to group artists based on their streaming behaviors. The dataset is also handled for class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique) to improve model accuracy.

## Libraries Used

- **Pandas**: Data manipulation and analysis
- **Numpy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Plotly**: Interactive visualizations
- **Scikit-learn**: Machine learning models and evaluation
  - Models: Random Forest, SVM, KNN, Logistic Regression
  - Preprocessing: MinMaxScaler, StandardScaler, LabelEncoder
  - Evaluation: Cross-validation, classification report, confusion matrix
- **Keras**: Building and training neural networks
- **Imbalanced-learn (SMOTE)**: Handling class imbalance
- **PCA (Principal Component Analysis)**: Dimensionality reduction for feature analysis
- **KMeans**: Clustering algorithm for segmenting artists
