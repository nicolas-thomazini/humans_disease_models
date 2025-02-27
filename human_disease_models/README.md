# Disease Human Model

This is the first model. In this model, we trained a model with a dataset of some disease which Influenza, Asthma, Hyperthyroidism and other diseases.

## 1. Introduction

The model was based in dataset disease_symptom.csv that contains sympotoms and the diseases that a person has, and the target variables is based on feature "outcome_variable".

The other features will be used to be the independent variables that used in dependence variable (target variable).

## 2. Dependences

The dependences of projects can be find in "requirementx.txt". For install it, open the Prompt Command:

1. If you want to use a independent virtual envirtoment, you can create a venv:

    If you use python3:
    ~~~bash
    python3 -m venv venv 
    ~~~

    If you use python:
    ~~~bash
    python -m venv venv 
    ~~~
    >**Note:** You can see venv it's repeated, but the firts venv it's the command and the second venv it's the enviroment that you created.


2. Run:
    ~~~bash 
    pip install -r requirements.txt
    ~~~ 
    All libraries used in project now it's install.

## 3. Dataset *disease_symptom.csv*

The dataset contains diseases and symptoms the person has wen he/she been sick. The outcome_variable is the responsable for determinate if the person be sicked of the disease or not.

## 4. Model

The dataset contains more features booleans then numerics. It's used algorithms of Classification for model.

The algorithms used for model it's Logistic Regression, Descision Tree. Random Forest and XGBoost.

For XGBoost and Rnadom Forest, for obtains the better perfomance, we tuning the model avaliating the parameters and adjust them for the numbers that they work better.

## 5. Clone Repository

If you want the model for study, you can clone the repository:

1. Open the Prompt Command.

2. You can run:
    ~~~bash
    git clone https://github.com/nicolas-thomazini/humans_disease_models
    ~~~

## 6. Branch *feature/disease-human-general*

Which the model it's a general disease that happening in humans, the model it's save in the branch *feature/disease-human-general*.