# datafun-07-ml

## Overview
This project focuses on implementing the guided projects 10.16, 15.4 and 15.5 from the textbook. 

### Objective:
 - Build a model
 - Make predictions
 - Visualize the model
 - Publish your insights

## Deliverables
- `datafun-07-ml`: Project repository
- `README.md`: Provides an overview of the project, as well as instructions for setting up and executing the environment.
- `requirements.txt`: Lists all packages required for the project.
- `jingyuan_ml.ipynb`: Jupyter Notebook file

## Environment Setup 

- Create a new GitHub repository named `datafun-07-ml`
- Add a default `README.md.`
- Clone the repository to your local machine.
```python
git clone https://github.com/JingyuanDainmsu/datafun-07-ml
```
- Create a Project Virtual Environment in the .venv folder.
```python
py -m venv .venv
```
- Activate the virtual environment
```python
.\.venv\Scripts\Activate
```
- Install dependencies into your `.venv` 
```python
pip install pandas pyarrow matplotlib scipy seaborn scikit-learn
```
- Freeze into requirements.txt.
```python
pip freeze > requirements.txt
```
- Add a useful .gitignore to the root project folder with `.vsode/` and `.venv/` to prevent adding to repository

- Git add and commit with a useful message (e.g. "initial commit") and push to GitHub.
    
    `git add .`
   
    `git commit -m "initial commit"`
   
    `git push origin main`
   
## Project Organization & Data Files

- Access and download associated files and data from [IntroToPython/examples](https://github.com/pdeitel/IntroToPython/tree/master/examples)
- Create `examples` subfolder in the root project repository folder: `datafun-07-ml`
- Add downloaded associated files and data to the `examples` subfolder

## Start the Project

- Open `datafun-07-ml` root project repository in VS code
- Create new notebook in root project repository named: `jingyuan_ml.ipynb`
- Add cell with import statements
```python
from matplotlib import pyplot as plt
import pandas as pd
import pyarrow
from scipy import stats
import seaborn as sns
import sklearn
from sklearn.model_selection import train_test_split
```

## Analysis Workflow

### CC 7.5:  Chart a Straight Line (Part 1)
- Complete section per Project 7 requirements

### CC 7.6:  Predict Avg High Temp in NYC in January (Part 2)
- Complete section per Project 7 requirements for Object-Oriented Programming
    1. Build a model
    2. Make predictions
    3. Visualize the model

### CC 7.7: Predict Avg High Temp in NYC in January (Part 3)
- Complete section per Project 7 requirements for Supervised Machine Learning
    1. Build a model
    2. Make predictions
    3. Visualize the model

### CC 7.8: Insights (Part 4)
- Complete section per Project 7 requirements
    1. Publish insights

### Optional Bonus (Part 5)
- Complete section per Project 7 requirements
    1. Loading the data
    2. Training and testing the data
    3. Visualizing the data
    4. Choosing the best model from the 4 listed
