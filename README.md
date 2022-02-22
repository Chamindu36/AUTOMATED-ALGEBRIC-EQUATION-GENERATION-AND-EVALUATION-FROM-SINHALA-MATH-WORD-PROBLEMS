# Automated Algebraic Equation Generation And Evaluation From Sinhala Math Word Problems

## Introduction

A system which solves simple
algebraic equations and classifies the types of simultaneous
equations. Preprocesses questions and numerical values will be
mapped to an equation and output the answer. Two approaches
were used for simultaneous equation classification, Dynamic
approach, and rule-based approach. Five pre-defined equations
types have been used for the classification. In rule-based
approach values extracted from the questions will be mapped a
template based on defined set of rules. Dynamic approach will
use ANN model for equation classification.


## How to Setup
1. Please refer the steps mentioned in https://colab.research.google.com/drive/179ypZund7SiDDw0Sq_O_Eq_qVr_uRrJ-?usp=sharing and get the required python packages.
2. Install Nvidia CUDA.

3. install nltk 3.2.5.

```!pip install nltk==3.2.5```

4. Install the tensorflow 2.0.0 and keras 2.3.1.

```!pip install tensorflow==2.0.0```
```!pip install keras==2.3.1```

5. Install scikit-learn 0.22.2 and numpy 1.18.1.

`!pip install scikit-learn==0.22.2`
`!pip install numpy==1.18.1`

6. Clone the repo.
7. Change main path to your loacl setup.
8. Build python project.

## How to run the tool
1. Wait until the GUI appears.
2. Check the samples provided in the Testing folder and create your question and paste the question into a text file.
3. Check radio button to notify whether the question is a simple one or complex one.
4. Then upload the created the text file with question.

