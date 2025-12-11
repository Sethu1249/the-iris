# the-iris
Project Overview

This repository contains the full code and written tutorial for the assignment exploring:

“How Kernel Choice Affects Support Vector Machine (SVM) Performance — Using the Iris Dataset.”

The tutorial focuses on teaching how different SVM kernels
(Linear, RBF, Polynomial, Sigmoid)
influence:

Decision boundaries

Model behaviour

Accuracy and generalization

Hyperparameter sensitivity (C, gamma, degree)

The written tutorial document is included:
irisreport.docx 

irisreport


and is intended for evaluation as part of the coursework submission.

All experiments are implemented in the Jupyter notebook:
the_iris.ipynb (uploaded as the_iris (2).ipynb).
Dataset used: Iris.csv.
epository Contents
File	Description
irisreport.docx	Full tutorial explaining SVM kernels and results 

irisreport


the_iris.ipynb	Executable notebook with code for training, evaluation, and visualization
Iris.csv	Dataset used for the experiments
README.md	Documentation for using this repository
LICENSE	Open-source license file (MIT recommended)
Learning Objectives Addressed

This repository demonstrates the ability to:

Explain the mechanics of SVMs and kernels

Implement ML models professionally using Python + scikit-learn

Critically compare modelling choices

Use visualization to communicate concepts clearly

Produce reproducible, accessible educational material

Reflect on ethical + practical considerations in ML
Technique Summary (What This Repository Teaches)

Support Vector Machines classify data by finding an optimal margin. When data isn't linearly separable, kernels transform the feature space.

This project compares four kernels:

Linear – simple, fast, effective on separable data

Polynomial – introduces curvature; may overfit

RBF (Gaussian) – flexible and typically most accurate

Sigmoid – behaves like neural activations; unstable in practice

Visualizations include:

2D decision boundaries

Confusion matrices

Cross-validated accuracy curves

All of these support the tutorial’s teaching goal:
to show why kernel choice matters and how to select one.
nstallation & Requirements
1. Clone this repository
git clone <your-repo-url>
cd <repo>

2. Install dependencies

Recommended environment: Python 3.9+

pip install -r requirements.txt


Typical required packages:

scikit-learn
numpy
pandas
matplotlib
seaborn

3. Run the Jupyter notebook
jupyter notebook the_iris.ipynb


All plots shown in the tutorial will be reproduced automatically.

📊 How to Use the Notebook

Load and inspect the Iris dataset

Standardize features

Train SVM models with different kernels

Run GridSearchCV over C, gamma, degree

Plot decision boundaries and accuracy curves

Evaluate on a held-out test set

All steps include clear comments to support reuse.

♿ Accessibility Measures

To meet assignment accessibility requirements, the project includes:

High-contrast, colour-blind-friendly plots

Alt-text style descriptions for figures in the written tutorial

Clear headings and semantic structure

Screen-reader-friendly document formatting

Non-audio-dependent content (for students with hearing difficulties)

This project is distributed under the MIT License.
You may freely reuse and modify the code with proper attribution.


The full reference list appears in irisreport.docx 

irisreport

.
Key sources include:

Cortes, C. & Vapnik, V. (1995). Support-Vector Networks.

Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python.

scikit-learn documentation: https://scikit-learn.org/stable/modules/svm.html
https://github.com/Sethu1249/the-iris
