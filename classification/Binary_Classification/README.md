# Classification Predictive Modeling ML problem

## Problem Definition

The focus of this project will be the Sonar Mines vs Rocks dataset 1 . The problem is to predict
metal or rock objects from sonar return data. Each pattern is a set of 60 numbers in the range
0.0 to 1.0. Each number represents the energy within a particular frequency band, integrated
over a certain period of time. The label associated with each record contains the letter R if
the object is a rock and M if it is a mine (metal cylinder). The numbers in the labels are in
increasing order of aspect angle, but they do not encode the angle directly.


### Summary

In this tutorial we worked through a Logistic predictive modeling machine learning problem
from end-to-end using Python. Specifically, the steps covered were:

* Problem Definition (Sonar return data).
* Loading the Dataset.
* Analyze Data (same scale but different distributions of data).
* Evaluate Algorithms (KNN looked good).
* Evaluate Algorithms with Standardization (KNN and SVM looked good).
* Algorithm Tuning (K=1 for KNN was good, SVM with an RBF kernel and C=1.5 was
best).
* Finalize Model (use all training data and confirm using validation dataset).
* Finalize Model (use all training data and confirm using validation dataset).


Working through this case study approach showed you how the steps for specific machine learning
tasks can be pulled together into a complete project. Working through this case study is good
practice at applied machine learning using Python and scikit-learn.


#### Required python version
```sh
$ python --version
Python 3.5.5
```

### Steps to setup
Clone repo ...

```sh
$ git clone https://purushottam-bitle@github.com/purushottam-bitle/machine-learning-projects.git
```

##### Create new virtual env using anaconda
```sh
$ conda create --name <proj_name35> python=3.5
```

##### Activate virtual env
```sh
$ source activate <proj_name35>
```

##### Install libraries

```sh
$ pip install -r requirements.txt
```

##### Create and Deploy the Service to nginx server so that it accepts multiple requests
```sh
https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04
```


