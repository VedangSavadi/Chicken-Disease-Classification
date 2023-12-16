# Chicken-Disease-Classification

## Workflows

1. Update config.yaml
2. Update secrets.yaml [optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. update the dvc.yaml

# How to run?

## STEPS:
Clone the repository
https://github.com/VedangSavadi/Chicken-Disease-Classification

## STEP 01 - Create a conda evironment after opening the repository
conda create -n cnncls python=8.8 -y
conda activate cnncls

## STEP 02 - Install the requirements
pip install -r requirements.txt

## Finally run the following command
Python app.py

Now,
open up your local host and port

## DVC cmd
1. dvc init
2. dvc repro
3. dvc dag