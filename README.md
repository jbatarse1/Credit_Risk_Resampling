# Credit_Risk_Resampling

This Python application is to validate the performance of a predictive logistic regression model. This program runs in Jupyter Lab.

It uses dataset manipulation and resampling methods to perform analysis; and uses a correlation to validate if any predictable relationship exists between Loan Status trends and the exposure to high risk loan defaults.

Also, reporting techniques for both models are created to predict loan status and creditworthiness of borrowers.

Finally, a report called the Overview of the Analysis is provided.



## Technologies

This application incorportates the following required  dependancies to run:

### Import the required libraries and dependencies for Python

`import numpy as np`

`import pandas as pd`

`from pathlib import Path`

`from sklearn.metrics import balanced_accuracy_score`

`from sklearn.metrics import confusion_matrix`

`from imblearn.metrics import classification_report_imbalanced`

`import warnings
`warnings.filterwarnings('ignore')`


## Installation Guide

The following installation must be performed before running the program. It include:

### Install the required libraries 

`imbalanced-learn`

`PyDotPlus`

## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment and 

Resources folder contains the following CSV files:

`lending_data.csv`


The following information evaluates the results of both models:


Original data for model:
<img width="753" alt="Original Data" src="https://user-images.githubusercontent.com/93550651/160334104-61071e6f-7c73-492a-9bac-6a9d4792ea4a.png">


Resampled data for model:
<img width="753" alt="Resampling of Data" src="https://user-images.githubusercontent.com/93550651/160334164-12ee945f-cff9-4f9d-9c60-215a6bee9d46.png">



## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License

Trilogy Education LLC. and UC Berkeley

