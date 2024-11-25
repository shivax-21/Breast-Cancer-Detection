# 🩺Breast-cancer-Detection-Model
## Overview
This project is a machine learning-based solution for detecting breast tumors. Using Logistic Regression, we predict whether a breast tumor is malignant or benign. The project also includes detailed data visualization to understand the patterns and correlations in the dataset.  Using a dataset from Kaggle (download it from [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) or used the csv file of this repository.
## What’s Inside
### This project includes:
* Data Preprocessing: Handles missing values, scaling, and data transformation.
* Machine Learning Model: Implements Logistic Regression for classification.
* Performance Metrics: Evaluates the model using accuracy, precision, recall, and ROC-AUC score.
## Tools & Libraries
#### Here’s what I used to bring this project to life:
* Python: The core programming language.
* Jupyter Notebook: For coding and experimenting.
* Pandas: To handle and explore the data.
* Numpy: For all the number crunching.
* Scikit-learn: To build and evaluate the models.
## Algorithms Used
Logistic Regression: Chosen for its simplicity and interpretability in binary classification problems.

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
 ```bash
git clone https://github.com/shivax-21/Breast-cancer-Detection.git
 ```
2. Navigate to the project folder:
``` bash
cd Breast-cancer-Detection
```
3. Install the necessary libraries:
``` bash
pip install numpy pandas scikit-learn
```
## Usage
1. Download the Dataset: Make sure you have the Kaggle dataset file [this](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) in the same directory as the notebook.

2. Launch Jupyter Notebook:
``` bash
jupyter notebook
```
3. Open the Notebook: Navigate to `notebook.ipynb` in Jupyter.
4. Run the Cells: Execute the cells in the notebook to train the model and see the magic.
## Results
Achieved an accuracy of ~95% on the test dataset.
High precision and recall, making the model reliable for tumor detection.
## Future Improvements
Experiment with other ML algorithms like SVM, Random Forest, or Neural Networks.
Deploy the model as a web app for easier accessibility.
Include more advanced feature selection methods.
## Contributing
Feel free to fork this repository, create a feature branch, and submit a pull request! Contributions are always welcome.


