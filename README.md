# ouroboros_fmri

## Ouroboros fMRI: Predicting human brain activity with machine learning models

Version: 10th March 2021

Project developed by Maël Donoso, Ph.D. in Cognitive and Computational Neuroscience. Affiliations: Ouroboros Neurotechnologies (https://ouroboros-neurotechnologies.com/), Institut Lémanique du Cerveau (https://institut-cerveau.ch/), Policlinique Ostéopathique de Lausanne (https://policlinique-osteopathique-lausanne.ch/). The first version of this project (17th February 2021) was presented as a Capstone Project for the COS in Applied Data Science: Machine Learning of the EPFL Extension School (https://www.extensionschool.ch/).

### Abstract

This project uses data science (NumPy, Pandas, Matplotlib), machine learning (Scikit-Learn) and deep learning (TensorFlow) tools on statistical maps of the human brain obtained with functional Magnetic Resonance Imaging (fMRI). Our objective is to train machine learning models to recognize and predict brain activity, using a dataset from the open data repository NeuroVault. Specifically, we use machine learning models to classify brain images, and to predict the values of voxels inside these brain images. Our results show that both classification and regression are possible, suggesting that the statistical maps obtained in this experimental setup contain relevant and generalizable knowledge about the brain activity. 

### Structure and dependencies

This project is organized through a series of six JupyterLab Notebooks, to be run in order:

- 01. Data Analysis
- 02. Classification
- 03. Neural Networks
- 04. Regression
- 05. Results
- 06. Complements

Dependencies:

- python=3.6
- numpy=1.15
- scipy=1.2
- pandas=0.24
- matplotlib=3.0
- seaborn=0.9
- jupyterlab=2.1
- notebook=6
- scikit-learn=0.20
- tensorflow=1.12
- tensorflow-hub=0.4.0
- requests=2.20
- pillow=5.3
- graphviz=2.38
- python-graphviz=0.8.4
- pip=18.1
- tqdm
