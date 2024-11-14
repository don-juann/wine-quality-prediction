# Wine Quality Prediction
Aim of this project is to apply machine learning algorithms in order to predict the quality of red wine based on various chemical properties.
The dataset contains features such as acidity, sugar levels, pH, alcohol content, and more. The goal is to create model that will calssify wines into different quality categories.

## Dataset
Source: UCI Machine Learning Repository
Description: The dataset includes chemical characteristics of red wines along with quality ratings ranging from 3 to 8. 
Feature names:
fixed acidity, volatile acidity, citric acid, residual sugar, chlorides
free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol
Target: quality (wine quality score from 3 to 8)

## Project Structure
### Data Exploration and Visualization
The file contains statistical summaries and visualization to understand the dataset.
MatPlotLib plots provide interesting insights regarding features, their relationship and are described in Python comments.

### Data Preprocessing
Certain transformations were applied for skewed features to increase data representativeness.
Also, stratified sampling was used to balance the distribution of categories.

### Modeling
Multiple machine learning models are explored, including decision trees, random forests, and logistic regression.
Evaluation of model performance was conducted based on metrics such as accuracy, precision, recall and F1-score.

### Evaluation and Insights
Analysis of model performance and feature importance.
Conclusions on what kind of features significantly impact wine quality.

### Installation
To run this project, install the necessary packages:
`
pip install pandas numpy matplotlib scikit-learn
`
Clone the repository and navigate to the project directory.
Run the notebook to see data visualizations, model training, and evaluation results.

OR, if you are using Google Colaboratory: 
- Upload the .ipynb file
- Open the file
- Press CTRL+F9 to run all cells

## Results
Key insights from this analysis include:
Ranking of feature importance and correlations quality of the wine.
Model comparisons, fine-tuning and choosing the best-performing model for prediction.

## Acknowledgements
Dataset was provided by the UCI Machine Learning Repository and published on Kaggle.

- Zhan Kazikhanov (Astana IT University)
- jkazikhanov@gmail.com
- https://github.com/don-juann
