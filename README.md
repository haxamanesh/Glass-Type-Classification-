# Glass Classification

This project aims to classify different types of glass using machine learning models. The dataset used contains various features of glass samples, and the goal is to predict the type of glass based on these features.

## Table of Contents

- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models](#models)
- [Evaluation](#evaluation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

## Dataset

The dataset used is `glass_data.csv`. It contains the following features:

- **RI**: Refractive index
- **Na**: Sodium content
- **Mg**: Magnesium content
- **Al**: Aluminum content
- **Si**: Silicon content
- **K**: Potassium content
- **Ca**: Calcium content
- **Ba**: Barium content
- **Fe**: Iron content
- **Type of glass**: Target variable (type of glass)

## Preprocessing

The following preprocessing steps are performed:

- Removing unnecessary columns (e.g., "id number").
- Checking for missing values and duplicates.
- Exploring the distribution of features using histograms.
- Standardizing the features using `StandardScaler`.

## Models

Several machine learning models are trained and evaluated:

- Support Vector Machine (SVM)
- Gradient Boosting Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Multi-Layer Perceptron (Neural Network)

## Evaluation

The accuracy score is used to evaluate the performance of each model. The results are summarized in a pandas DataFrame.

## How to Run

1. Make sure you have the required libraries installed: `pandas`, `numpy`, `matplotlib`, `tensorflow`, `scikit-learn`, `xgboost`.
2. Download the `glass_data.csv` dataset and place it in the same directory as the code.
3. Run the code in a Jupyter Notebook or Google Colab environment.

## Results

The accuracy scores for each model are displayed in the output. You can compare the performance of different models and choose the best one for your application.

## Future Work

- Explore hyperparameter tuning to further improve model performance.
- Try other classification algorithms.
- Visualize the decision boundaries of the models.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
