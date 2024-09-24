# Raisin Classification with Hyperparameter Tuning

## Project Overview

This project aims to classify two types of raisin grains—Kecimen and Besni—using a dataset containing morphological features. We utilize machine learning models and hyperparameter tuning techniques to achieve optimal classification performance. The dataset consists of 900 samples, equally distributed between the two classes, and includes seven numerical features describing each raisin sample.

## Objectives

- Explore the dataset and understand the distribution of features.
- Preprocess the data to prepare it for model training.
- Implement machine learning models to classify raisin types.
- Tune hyperparameters using Grid Search and Random Search to enhance model performance.
- Evaluate models using metrics like accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project contains the following features:

- **Area**: Area of the raisin grain.
- **MajorAxisLength**: Length of the major axis of the raisin grain.
- **MinorAxisLength**: Length of the minor axis of the raisin grain.
- **Eccentricity**: Eccentricity of the raisin grain.
- **ConvexArea**: Convex area of the raisin grain.
- **Extent**: Extent of the raisin grain.
- **Perimeter**: Perimeter of the raisin grain.
- **Class**: Type of raisin (Kecimen or Besni).

The dataset can be accessed at: [Raisin Dataset](https://www.muratkoklu.com/datasets/)

## Methodology

- **Data Exploration and Visualization**: Understanding the data distribution and identifying relationships between features.
- **Data Preprocessing**: Standardizing and normalizing features, and encoding the target variable.
- **Model Training**: Implementing machine learning models including Decision Tree and Logistic Regression.
- **Hyperparameter Tuning**: Using Grid Search and Random Search to find the best model parameters.
- **Model Evaluation**: Assessing model performance using confusion matrices, ROC curves, and other metrics.

## Hyperparameter Tuning

- **Grid Search**: Used to optimize the hyperparameters of a Decision Tree classifier.
- **Random Search**: Applied to a Logistic Regression model to identify the best hyperparameters.

## Results

The best-performing model achieved an accuracy of `XX%` on the test set. The Decision Tree model, with optimized hyperparameters, showed the highest classification accuracy, indicating that features like **Area** and **Perimeter** are effective predictors of raisin type.

## Conclusion

This project demonstrates the process of building, optimizing, and evaluating machine learning models for a classification task. The results highlight the importance of feature engineering and hyperparameter tuning in improving model performance. Future work could involve incorporating additional features or exploring advanced models like Support Vector Machines or ensemble methods.

## Future Work

- **Feature Expansion**: Incorporate additional features like texture and color.
- **Advanced Models**: Explore complex models like SVM or ensemble methods.
- **Cross-Validation**: Implement cross-validation techniques for model robustness.

## Installation and Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook to explore the analysis:
    ```bash
    jupyter notebook Classify-Raisin-Class-With-Hyperparameter-Tuning.ipynb
    ```

## Citation

If you use this project or dataset in your research, please cite:

CINAR I., KOKLU M. and TASDEMIR S., (2020). Classification of Raisin Grains Using Machine Vision and Artificial Intelligence Methods, Gazi Journal of Engineering Sciences, vol. 6, no. 3, pp. 200-209, December, 2020, DOI: https://doi.org/10.30855/gmbd.2020.03.03

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributions
