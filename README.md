# Support Vector Machine on Mushroom Dataset

## Project Overview
This project demonstrates the implementation of a Support Vector Machine (SVM) classifier to analyze and classify data from the Mushroom Dataset. The dataset provides information on various features of mushrooms, and the goal is to predict whether a mushroom is edible or poisonous.

## Features
- **Exploratory Data Analysis (EDA):** Visualize and analyze the dataset to understand feature distributions and correlations.  
- **Data Preprocessing:** Prepare the dataset for machine learning by encoding categorical variables and splitting data into training and testing sets.  
- **SVM Implementation:** Train and evaluate an SVM classifier using Python and scikit-learn.  
- **Visualization:** Showcase results through plots and graphical representation of classifications.  
- **Hyperparameter Tuning:** Experiment with different SVM parameters to optimize performance.  
- **Comparison:** Analyze the effect of different kernels and discuss SVM's practical implications.  

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git  
   cd your-repo-name  
Usage
Download the Mushroom dataset from UCI Machine Learning Repository and place it in the data/ directory.
Run the script to perform the analysis and visualize results:
bash
Copy code
python main.py  
Results and visualizations will be saved in the results/ directory.
Project Structure
graphql
Copy code
.
├── data/                   # Folder for the Mushroom dataset  
├── results/                # Folder for generated visualizations and outputs  
├── main.py                 # Main script for running the SVM analysis  
├── utils.py                # Helper functions for preprocessing and visualization  
├── README.md               # Project documentation  
└── requirements.txt        # List of Python dependencies  
Key Steps
Dataset Selection: Mushroom dataset from UCI Repository.
EDA: Histograms, box plots, density plots, and correlation matrices.
Data Preprocessing: Categorical encoding and train-test split.
SVM Implementation: Basic classifier using scikit-learn.
Visualization: Scatter plots, class distributions, and classification results.
Hyperparameter Tuning: Optimization of kernel type, regularization parameters, etc.
Comparison: Evaluation of different kernels and their impact.
Dependencies
Python 3.x
scikit-learn
pandas
numpy
matplotlib
seaborn
Install dependencies using:

bash
Copy code
pip install -r requirements.txt  
Results
Performance metrics: Accuracy, Precision, Recall, F1-score.
Visualizations of classifications and decision boundaries.
Comparison of different SVM kernels.
