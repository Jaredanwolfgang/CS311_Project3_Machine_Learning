# CS311 Project 3: Classification
This is the repository for the project 3 of the CS311. In this project, we are asked to learn a model on an Adult Census Income dataset, and the goal is to predict whether income exceeds \$50K/yr based on census data. The original data is from kaggle [Adult Census Income]("https://www.kaggle.com/datasets/uciml/adult-census-income"). I try to utilize this chance to enhance my understanding on different models and how they perform, and try to figure out the reasons to their performance behaviors.

## Environment

This project is written in Jupyter Notebook and the environment is managed by conda. You can create a conda environment by:

    conda create -n CS311_proj3 python=3.8

Then you can download the package need in this project:

    conda install pandas
    conda install numpy
    conda install scikit-learn
    conda install graphviz
    conda install python-graphviz
    conda install seaborn

The conda version is `24.4.0`. After setting up all the environments and ensure the dependencies are suitable for all packages, you can run the program! 

## Models

- [x] Decision Tree
- [x] Naive Bayes
- [x] Nearest Neighbors 
- [x] Ensemble Models
- [x] Support Vector Machine
- [x] Neuron Networks

## Best performance

The best performance is runned with Random Forest Classifiers with max depth of 16, the result is 0.8659. For further information please checkout the report. 

> ## Importance!
> The `testlabel_from_kaggle.txt` is referenced answer from kaggle, the actual testlabel is stored in `testlabel.txt` file. 