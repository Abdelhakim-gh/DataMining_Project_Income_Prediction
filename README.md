# DataMining_Project_Income_Prediction

This project aims to predict income levels based on various demographic and other features using data mining techniques.

## Project Structure

```
Data/
    data_n_missing_1.csv
    data_n_missing_2_encoded_.csv
    data_pca.csv
    data_selected_features.csv
    data_smote.csv
    Income_category.csv
    test_data.csv
    train_data.csv
    val_data.csv

DM_project.ipynb
label_encoders.pkl
ordinal_encoder.pkl
README.md
```

### Data Files

- **data_n_missing_1.csv**: Dataset without missing values.
- **data*n_missing_2_encoded*.csv**: Encoded dataset with missing values handled.
- **data_pca.csv**: Dataset after applying PCA for dimensionality reduction.
- **data_selected_features.csv**: Dataset with selected features for modeling.
- **data_smote.csv**: Dataset after applying SMOTE for handling imbalanced data.
- **Income_category.csv**: Dataset with income categories.
- **test_data.csv**: Test dataset.
- **train_data.csv**: Training dataset.
- **val_data.csv**: Validation dataset.

### Notebooks

- **DM_project.ipynb**: Jupyter notebook containing the data mining project, including data loading, preprocessing, visualization, modeling, and evaluation.

### Encoders

- **label_encoders.pkl**: Pickle file containing label encoders for categorical features.
- **ordinal_encoder.pkl**: Pickle file containing ordinal encoder for ordinal features.

## Getting Started

1. Clone the repository.
2. Install the required dependencies.
3. Open `DM_project.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook cells to reproduce the analysis and results.

## Dependencies

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- pickle
- dtale
- imbalanced-learn
- keras
- tensorflow

## Project Steps

- **Data Loading and Exploration**: Load and explore the dataset.
- **Data Visualization**: Visualize the data distributions and relationships (EDA).
- **Data Cleaning**: Handle missing values and outliers.
- **Handling Imbalanced Data**: Apply techniques like SMOTE to balance the data.
- **Data Transformation**: Normalize and encode features.
- **Feature Engineering**: Create and select features for modeling.
- **Model Training and Evaluation**: Train and evaluate various classification models and ANN.
- **Fine Tuning**: Adjust model hyperparameters and select the best performing model.
- **Results Interpretation**: Interpret and visualize the results.
