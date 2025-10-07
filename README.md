# Misinformation Detection on Social Media

This project presents a machine learning pipeline designed to detect misinformation on social media platforms. 
The system processes social media data stored in .xlsx datasets, applies data preprocessing, feature 
engineering, and trains machine learning models using pandas, scikit-learn and other Python libraries within 
a Jupyter Notebook environment.


## Project Overview

The rapid dissemination of misinformation on social media is a growing concern. This project employs supervised 
machine learning techniques to classify content as either `fake` or `real`, using labelled datasets 
stored in Microsoft Excel (.xlsx) format.


### Features
- Data Loading and Processing: Reads .xlsx datasets utilising pandas.
- Feature Engineering: Cleans and transforms textual and metadata for machine learning.
- Model Training: Implements algorithms from scikit-learn.
- Evaluation: Produces accuracy metrics, confusion matrices, and other performance indicators.
- Interactive Analysis: Entire workflow contained within a Jupyter Notebook for ease of experimentation and
reproducibility.

#### How to run the code
1. Download Python
2. Downlaod Jupyter Notebook
3. Download conda from: https://www.anaconda.com/ or https://docs.conda.io/en/latest/miniconda.html
4. Create new Conda environment:
```
conda create --name myenv python=3.11
```
5. Activate conda:
```
conda activate myenv
```
3. Install required packages: 
```
pip install pandas numpy seaborn matplotlib scikit-learn openpyxl jupyter
```
4. Run all the code 
