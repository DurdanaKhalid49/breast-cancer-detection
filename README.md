Breast Cancer Detection Project

Overview

This project aims to detect breast cancer using the load_breast_cancer dataset provided by scikit-learn. The dataset includes various features describing cell nuclei and a target label indicating whether the sample is malignant or benign.

Dataset

Source: scikit-learn's load_breast_cancer dataset

Features: 30 numerical features such as mean radius, mean texture, mean smoothness, etc.

Target: Binary classification (0 = Malignant, 1 = Benign)

Steps in the Notebook

Data Loading:

Import the dataset using load_breast_cancer.

Create a DataFrame for easy manipulation and exploration.

Data Exploration:

Print dataset details (description, feature names, and target).

Check data shape and head/tail of the DataFrame.

Data Visualization:

Pairplots to explore feature distributions.

Heatmap to analyze feature correlations.

Scatter plots and count plots to examine relationships.

Model Building (optional, if added later):

Train machine learning models to classify samples as malignant or benign.

Requirements

Install the required dependencies using the following command:

pip install -r requirements.txt

How to Run the Notebook

Clone the repository:

git clone https://github.com/yourusername/breast-cancer-detection.git

Navigate to the project directory:

cd breast-cancer-detection

Install dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook Breast_cancer_detection.ipynb

Results

Detailed visualizations of the dataset.

Insights into the correlation between features.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

scikit-learn for providing the dataset.

Libraries used: pandas, numpy, matplotlib, seaborn.

