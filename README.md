# ML Ops Assignment 1 
This repo contains the solution to the MLOps Assignment 1. I have used the Boston Housing Dataset for this task.
In this assigment we have worked with multiple git branches and implemented the Github Actions Workflow with kernelridge branch.

## Steps to train DecisionTreeRegressor model

Step_1: Clone this public repo by using the git clone command.\
Step_2: Goto the cloned directory.\
Step_3: Open the terminal and create a conda env.
```bash
conda create -y -n myconda-env1 python=3.11
conda activate myconda-env1
```
Step_4: Install the dependencies.
```bash
pip install -r requirements.txt
```
Step_5: To train DecisionTreeRegressor use the command.
```bash
python train.py
```


## Steps to train KernelRidge model

Step_1: Clone this public repo by using the git clone command.\
Step_2: Goto the cloned directory.\
Step_3: Switch to kernelridge branch.\
Step_4: Open the terminal and create a conda env.
```bash
conda create -y -n myconda-env2 python=3.11
conda activate myconda-env2
```
##
Step_4: Install the dependencies.
```bash
pip install -r requirements.txt
```
##
Step_5: To train KernelRidge use the command.
```bash
python train2.py
```

## Steps to check Github Actions Workflow

Step_1: Clone this public repo by using the git clone command.\
Step_2: Goto the cloned directory.\
Step_3: Switch to kernelridge branch.\
Step_4: Open the terminal and create a conda env.
```bash
conda create -y -n myconda-env3 python=3.11
conda activate myconda-env3
```
##
Step_5: Add a test file, commit and Push it.\
##
Step_6: Goto Github Actions Workflow Page and see the workflow triggered.\